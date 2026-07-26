# username.github.io
<!doctype html>
<html lang="en"><head><script>window["__codeletBootstrap__"]=JSON.parse('{"A":"A","B":"20260723-05-e9a76f4"}');</script><script src="/_sdk/e358eac22bd01364.telemetry_sdk.js" integrity="sha512-KPxp3rw4K8Nu9ceWJc3gyM7srgaZxiFWOVbyu260EYzzAqdz10mfo5xyXrCx+wEKtGo77JbtmwXvFLbwrGzwvw=="></script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alex Popescu — Medical Networking</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&amp;display=swap" rel="stylesheet">
  <style>
    :root {
      --navy: #102a43;
      --ink: #1f3549;
      --muted: #64748b;
      --teal: #0f8b8d;
      --teal-dark: #0b7173;
      --teal-soft: #e8f6f5;
      --line: #dde5ea;
      --card: #ffffff;
    }

    * { box-sizing: border-box; }

    body {
      width: 100%;
      margin: 0;
      color: var(--ink);
      font-family: "DM Sans", sans-serif;
      background-color: #ffffff;
      background-image:
        linear-gradient(rgba(15, 139, 141, 0.035) 1px, transparent 1px),
        linear-gradient(90deg, rgba(15, 139, 141, 0.035) 1px, transparent 1px);
      background-size: 44px 44px;
    }

    .networking-page {
      width: 100%;
      min-height: calc(100 * min(var(--vh, 1vh), 1vh));
      padding: 44px 20px 28px;
    }

    .profile-ring {
      width: 112px;
      height: 112px;
      padding: 5px;
      background: linear-gradient(135deg, #d2f0ed, #0f8b8d);
      box-shadow: 0 14px 34px rgba(15, 139, 141, 0.14);
    }

    .profile-ring img {
      width: 100%;
      height: 100%;
      display: block;
      object-fit: cover;
      border: 4px solid #ffffff;
    }

    .content-card {
      border: 1px solid var(--line);
      box-shadow: 0 12px 28px rgba(16, 42, 67, 0.045);
    }

    .action-button {
      min-height: 86px;
      border: 1px solid var(--line);
      transition: transform 180ms ease, box-shadow 180ms ease, border-color 180ms ease, background 180ms ease;
    }

    .action-button:hover {
      transform: translateY(-3px);
      box-shadow: 0 13px 22px rgba(16, 42, 67, 0.1);
      border-color: #8ed7d3;
    }

    .action-button:focus-visible,
    .social-link:focus-visible {
      outline: 3px solid rgba(15, 139, 141, 0.28);
      outline-offset: 3px;
    }

    .primary-action:hover {
      background: var(--teal-dark) !important;
      border-color: var(--teal-dark);
    }

    .skill-pill {
      border: 1px solid #cce9e6;
      background: #f3fbfa;
    }

    .qr-grid {
      width: 92px;
      height: 92px;
      position: relative;
      overflow: hidden;
      background-color: #fff;
      background-image:
        linear-gradient(90deg, #102a43 10%, transparent 10%, transparent 20%, #102a43 20%, #102a43 30%, transparent 30%, transparent 40%, #102a43 40%, #102a43 50%, transparent 50%, transparent 60%, #102a43 60%, #102a43 70%, transparent 70%, transparent 80%, #102a43 80%, #102a43 90%, transparent 90%),
        linear-gradient(#102a43 10%, transparent 10%, transparent 20%, #102a43 20%, #102a43 30%, transparent 30%, transparent 40%, #102a43 40%, #102a43 50%, transparent 50%, transparent 60%, #102a43 60%, #102a43 70%, transparent 70%, transparent 80%, #102a43 80%, #102a43 90%, transparent 90%);
      background-size: 18px 18px;
      opacity: 0.9;
    }

    .qr-grid::before,
    .qr-grid::after {
      content: "";
      position: absolute;
      width: 28px;
      height: 28px;
      border: 6px solid #102a43;
      background: #fff;
    }

    .qr-grid::before {
      top: 6px;
      left: 6px;
    }

    .qr-grid::after {
      right: 6px;
      bottom: 6px;
    }

    .qr-center {
      position: absolute;
      top: 35px;
      left: 35px;
      width: 22px;
      height: 22px;
      border: 5px solid #102a43;
      background: #fff;
      z-index: 2;
    }

    .reveal {
      animation: rise-in 650ms ease both;
    }

    .reveal-delay-1 { animation-delay: 90ms; }
    .reveal-delay-2 { animation-delay: 160ms; }
    .reveal-delay-3 { animation-delay: 230ms; }
    .reveal-delay-4 { animation-delay: 300ms; }

    @keyframes rise-in {
      from { opacity: 0; transform: translateY(14px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 480px) {
      .networking-page { padding: 34px 16px 24px; }
      .profile-ring { width: 100px; height: 100px; }
    }

    @media (prefers-reduced-motion: reduce) {
      .reveal { animation: none; }
      .action-button { transition: none; }
    }
  </style>
  <script src="/_sdk/935a53bc2e11fb8d.data_sdk.js" type="text/javascript" integrity="sha512-qr2oyPnEys1WebcOABaRh6hG77r5PWpqeWW6JTKbRJqly/INsfBi31CVNlTmHqjgeLpkVmmHZJUdxSx/32tOFQ=="></script>
  <script src="/_sdk/6030e540d4419216.resizing_sdk.js" type="text/javascript" integrity="sha512-b5KWzyoXsbWP4smq4sftIi6Kts4YVBpBsz0BwCViwbBJkK64a3/Z6ZMdWA+qnplNcXw4mhZeqvQi3mOosiRJdA=="></script>
 </head>
 <body data-template-id="__page-root" style="background: rgb(255, 255, 255);">
  <div class="networking-page">
   <header class="w-full max-w-3xl mx-auto text-center">
    <div class="reveal">
     <div class="profile-ring rounded-full mx-auto"><img data-template-id="profile-photo" class="canva-image rounded-full" loading="lazy" src="https://images.pexels.com/photos/6762866/pexels-photo-6762866.jpeg" alt="Portrait of a confident young male doctor wearing eyeglasses and a white coat, arms crossed, in a studio setting.">
     </div>
     <h1 data-template-id="profile-name" class="canva-text mt-5 font-bold tracking-tight" style="color: rgb(16, 42, 67); font-weight: 700; font-style: normal; font-size: 32px; letter-spacing: -0.03rem;">Alex Popescu</h1>
     <p data-template-id="profile-subtitle" class="canva-text mt-1 font-medium" style="color: rgb(15, 139, 141); font-weight: 600; font-style: normal; font-size: 17px;">3rd Year Medical Student — TUM Munich</p>
     <p data-template-id="profile-tagline" class="canva-text mt-3" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 16px;">Aspiring Neurosurgeon | Clinical Research Enthusiast</p>
    </div>
   </header>
   <main class="w-full max-w-3xl mx-auto mt-11">
    <section aria-labelledby="quick-actions-heading" class="reveal reveal-delay-1">
     <div class="flex items-center gap-3 mb-4"><span class="w-7 h-px bg-teal-600"></span>
      <h2 id="quick-actions-heading" data-template-id="quick-actions-title" class="canva-text font-bold uppercase tracking-[0.16em]" style="color: rgb(100, 116, 139); font-weight: 700; font-style: normal; font-size: 13px; letter-spacing: 0.1rem;">Quick Actions</h2>
     </div>
     <div class="grid grid-cols-2 lg:grid-cols-4 gap-3"><button id="download-cv-button" type="button" data-template-id="download-cv-button" class="canva-button action-button primary-action rounded-2xl px-4 py-4 flex flex-col items-center justify-center gap-2 font-semibold" style="background: rgb(15, 139, 141); color: rgb(255, 255, 255);"> <i data-lucide="file-down" class="w-5 h-5" aria-hidden="true"></i> <span data-template-id="download-cv-label" class="canva-text" style="color: rgb(255, 255, 255); font-weight: 600; font-style: normal; font-size: 15px;">Download CV</span> </button> <a href="https://www.linkedin.com" target="_blank" rel="noopener noreferrer" data-template-id="linkedin-button" class="canva-button action-button rounded-2xl px-4 py-4 flex flex-col items-center justify-center gap-2 font-semibold text-center" style="background: rgb(255, 255, 255); color: rgb(16, 42, 67);"> <i data-lucide="linkedin" class="w-5 h-5" aria-hidden="true"></i> <span data-template-id="linkedin-label" class="canva-text" style="color: rgb(16, 42, 67); font-weight: 600; font-style: normal; font-size: 15px;">LinkedIn</span> </a> <button id="save-contact-button" type="button" data-template-id="save-contact-button" class="canva-button action-button rounded-2xl px-4 py-4 flex flex-col items-center justify-center gap-2 font-semibold" style="background: rgb(255, 255, 255); color: rgb(16, 42, 67);"> <i data-lucide="contact-round" class="w-5 h-5" aria-hidden="true"></i> <span data-template-id="save-contact-label" class="canva-text" style="color: rgb(16, 42, 67); font-weight: 600; font-style: normal; font-size: 15px;">Save My Contact</span> </button> <a href="mailto:alex.popescu@example.com?subject=Professional%20Networking%20Connection" data-template-id="email-button" class="canva-button action-button rounded-2xl px-4 py-4 flex flex-col items-center justify-center gap-2 font-semibold text-center" style="background: rgb(255, 255, 255); color: rgb(16, 42, 67);"> <i data-lucide="mail" class="w-5 h-5" aria-hidden="true"></i> <span data-template-id="email-label" class="canva-text" style="color: rgb(16, 42, 67); font-weight: 600; font-style: normal; font-size: 15px;">Email Me</span> </a>
     </div>
    </section>
    <section aria-labelledby="about-heading" class="mt-10 reveal reveal-delay-2">
     <article data-template-id="about-card" class="canva-card content-card rounded-3xl p-6 sm:p-8" style="background: rgb(255, 255, 255);">
      <div class="flex items-center gap-3 mb-4">
       <div class="w-9 h-9 rounded-xl bg-teal-50 text-teal-700 flex items-center justify-center"><i data-lucide="stethoscope" class="w-5 h-5" aria-hidden="true"></i>
       </div>
       <h2 id="about-heading" data-template-id="about-title" class="canva-text font-bold" style="color: rgb(16, 42, 67); font-weight: 700; font-style: normal; font-size: 24px;">About</h2>
      </div>
      <p data-template-id="about-copy" class="canva-text leading-7" style="color: rgb(82, 102, 122); font-weight: 400; font-style: normal; font-size: 16px; line-height: 1.7;">Medical student with strong interests in neurosurgery, clinical research, and academic collaboration. Open to connecting with mentors, peers, and research teams for learning opportunities, clinical exchange, and future projects.</p>
     </article>
    </section>
    <section aria-labelledby="skills-heading" class="mt-10 reveal reveal-delay-3">
     <div class="flex items-center gap-3 mb-4"><span class="w-7 h-px bg-teal-600"></span>
      <h2 id="skills-heading" data-template-id="skills-title" class="canva-text font-bold uppercase tracking-[0.16em]" style="color: rgb(100, 116, 139); font-weight: 700; font-style: normal; font-size: 13px; letter-spacing: 0.1rem;">Skills &amp; Languages</h2>
     </div>
     <div class="flex flex-wrap gap-2.5"><span data-template-id="skill-neurosurgery" class="canva-tag skill-pill rounded-full px-4 py-2 font-medium" style="background: rgb(243, 251, 250); color: rgb(11, 113, 115); font-weight: 600; font-style: normal; font-size: 14px;">Neurosurgery</span> <span data-template-id="skill-research" class="canva-tag skill-pill rounded-full px-4 py-2 font-medium" style="background: rgb(243, 251, 250); color: rgb(11, 113, 115); font-weight: 600; font-style: normal; font-size: 14px;">Clinical Research</span> <span data-template-id="skill-german" class="canva-tag skill-pill rounded-full px-4 py-2 font-medium" style="background: rgb(243, 251, 250); color: rgb(11, 113, 115); font-weight: 600; font-style: normal; font-size: 14px;">German B2</span> <span data-template-id="skill-romanian" class="canva-tag skill-pill rounded-full px-4 py-2 font-medium" style="background: rgb(243, 251, 250); color: rgb(11, 113, 115); font-weight: 600; font-style: normal; font-size: 14px;">Romanian Native</span> <span data-template-id="skill-venipuncture" class="canva-tag skill-pill rounded-full px-4 py-2 font-medium" style="background: rgb(243, 251, 250); color: rgb(11, 113, 115); font-weight: 600; font-style: normal; font-size: 14px;">Venipuncture Certified</span>
     </div>
    </section>
    <section aria-labelledby="rotation-heading" class="mt-10 reveal reveal-delay-3">
     <h2 id="rotation-heading" class="sr-only">Current Role and Rotation</h2>
     <div data-template-id="rotation-card" class="canva-card content-card rounded-2xl px-5 py-4 flex items-center gap-4" style="background: rgb(255, 255, 255);">
      <div class="w-10 h-10 shrink-0 rounded-xl bg-teal-50 text-teal-700 flex items-center justify-center"><i data-lucide="building-2" class="w-5 h-5" aria-hidden="true"></i>
      </div>
      <p data-template-id="rotation-copy" class="canva-text font-medium leading-6" style="color: rgb(37, 68, 94); font-weight: 600; font-style: normal; font-size: 16px;">Currently on Rotation: Neurosurgery Ward, TUM Munich</p>
     </div>
    </section>
    <section aria-labelledby="contact-heading" class="mt-10 reveal reveal-delay-4">
     <div data-template-id="contact-card" class="canva-card content-card rounded-3xl p-6 sm:p-7" style="background: rgb(255, 255, 255);">
      <div class="flex flex-col sm:flex-row sm:items-center gap-6">
       <div class="shrink-0 flex flex-col items-center text-center">
        <div class="p-2 rounded-xl border border-slate-200 bg-white">
         <div class="qr-grid" aria-hidden="true">
          <div class="qr-center"></div>
         </div>
        </div>
        <p data-template-id="qr-label" class="canva-text mt-3 font-semibold" style="color: rgb(16, 42, 67); font-weight: 600; font-style: normal; font-size: 13px;">Scan to Save Contact</p>
       </div>
       <div class="flex-1 min-w-0">
        <h2 id="contact-heading" data-template-id="contact-title" class="canva-text font-bold" style="color: rgb(16, 42, 67); font-weight: 700; font-style: normal; font-size: 24px;">Contact Exchange</h2>
        <p data-template-id="contact-copy" class="canva-text mt-2 leading-6" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 15px; line-height: 1.6;">A simple way to stay in touch for clinical conversations, research opportunities, and future academic collaboration.</p>
        <nav aria-label="Professional social links" class="mt-5 flex flex-wrap gap-x-5 gap-y-3"><a href="https://www.researchgate.net" target="_blank" rel="noopener noreferrer" data-template-id="researchgate-link" class="canva-link social-link inline-flex items-center gap-2 font-semibold" style="color: rgb(15, 139, 141);"> <i data-lucide="flask-conical" class="w-4 h-4" aria-hidden="true"></i> <span data-template-id="researchgate-label" class="canva-text" style="color: rgb(15, 139, 141); font-weight: 600; font-style: normal; font-size: 14px;">ResearchGate</span> </a> <a href="https://orcid.org" target="_blank" rel="noopener noreferrer" data-template-id="orcid-link" class="canva-link social-link inline-flex items-center gap-2 font-semibold" style="color: rgb(15, 139, 141);"> <i data-lucide="badge-check" class="w-4 h-4" aria-hidden="true"></i> <span data-template-id="orcid-label" class="canva-text" style="color: rgb(15, 139, 141); font-weight: 600; font-style: normal; font-size: 14px;">ORCID</span> </a> <a href="https://www.instagram.com" target="_blank" rel="noopener noreferrer" data-template-id="instagram-link" class="canva-link social-link inline-flex items-center gap-2 font-semibold" style="color: rgb(15, 139, 141);"> <i data-lucide="instagram" class="w-4 h-4" aria-hidden="true"></i> <span data-template-id="instagram-label" class="canva-text" style="color: rgb(15, 139, 141); font-weight: 600; font-style: normal; font-size: 14px;">Instagram</span> </a>
        </nav>
       </div>
      </div>
     </div>
    </section>
   </main>
   <footer class="w-full max-w-3xl mx-auto mt-12 pt-6 border-t border-slate-200 text-center">
    <p data-template-id="footer-copy" class="canva-text" style="color: rgb(123, 139, 155); font-weight: 400; font-style: normal; font-size: 14px;">Open to academic networking, research collaboration, and professional connection.</p>
   </footer>
  </div>
  <script src="/_sdk/c939c145c3c74230.editing_sdk.js" integrity="sha512-jh2pv/gl9Gzzn5dxfzwQO4wkqtnAQIim+LIUDYfVu2cdqPkQV2MqbjsDUW5IYbrSZFjRlOBrIWzlvWDXQYxOjg=="></script>
  <script>
    function downloadFile(filename, content, type) {
      const blob = new Blob([content], { type: type });
      const url = URL.createObjectURL(blob);
      const link = document.createElement("a");
      link.href = url;
      link.download = filename;
      document.body.appendChild(link);
      link.click();
      link.remove();
      URL.revokeObjectURL(url);
    }

    document.getElementById("download-cv-button").addEventListener("click", function () {
      const cvContent = [
        "ALEX POPESCU",
        "3rd Year Medical Student — TUM Munich",
        "Aspiring Neurosurgeon | Clinical Research Enthusiast",
        "",
        "PROFILE",
        "Medical student with strong interests in neurosurgery, clinical research, and academic collaboration.",
        "",
        "CURRENT ROLE",
        "Neurosurgery Ward Rotation, TUM Munich",
        "",
        "SKILLS & LANGUAGES",
        "Neurosurgery | Clinical Research | German B2 | Romanian Native | Venipuncture Certified",
        "",
        "CONTACT",
        "Email: alex.popescu@example.com"
      ].join("\n");

      downloadFile("Alex-Popescu-CV.txt", cvContent, "text/plain");
    });

    document.getElementById("save-contact-button").addEventListener("click", function () {
      const vCard = [
        "BEGIN:VCARD",
        "VERSION:3.0",
        "N:Popescu;Alex;;;",
        "FN:Alex Popescu",
        "TITLE:3rd Year Medical Student — TUM Munich",
        "EMAIL;TYPE=INTERNET:alex.popescu@example.com",
        "NOTE:Aspiring Neurosurgeon | Clinical Research Enthusiast",
        "END:VCARD"
      ].join("\r\n");

      downloadFile("Alex-Popescu-Contact.vcf", vCard, "text/vcard");
    });

    document.addEventListener("DOMContentLoaded", function () {
      lucide.createIcons();
    });
  </script>
 
</body></html>
