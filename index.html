// =========================================================
// Sturo — Portfolio script
// =========================================================

// ---------- Année du footer ----------
document.getElementById("year").textContent = new Date().getFullYear();

// ---------- Données des projets (vidéos à afficher) ----------
// Note : on pourra ré-affecter les shorts aux bons créateurs après confirmation.
const PROJECTS = {
  xelito: {
    layout: "shorts",
    videos: [
      "QLDkMZlmUog",
      "IXbsbsZowE8",
      "_rLHgYwtzx0",
      "3QkCtGP0CSI",
      "EBAz83E8R_8",
      "-C2YfX6dmls",
      "-bLgnbMVZLQ",
    ],
  },
  amixem: {
    layout: "shorts",
    videos: [
      "xeMlb-0vF1s",
      "4j5Up7_M9ik",
      "HaQ4qNunY3g",
      "T3qRaRWVrE4",
      "kfRCGWzNfQ4",
      "ofg4xTxQTZA",
      "gdF_RE1X5j8",
    ],
  },
  cube: {
    layout: "long",
    videos: ["3UBCl-jMl0E"],
  },
};

// ---------- Injection des embeds YouTube ----------
function buildEmbeds() {
  Object.entries(PROJECTS).forEach(([key, cfg]) => {
    const mount = document.querySelector(`[data-project="${key}"]`);
    if (!mount) return;
    if (cfg.layout === "long") mount.dataset.layout = "long";

    cfg.videos.forEach((id) => {
      const wrap = document.createElement("div");
      wrap.className = cfg.layout === "long" ? "embed-long" : "embed-short";

      const iframe = document.createElement("iframe");
      iframe.src = `https://www.youtube.com/embed/${id}?rel=0`;
      iframe.title = `Vidéo YouTube — ${key}`;
      iframe.allow = "accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share";
      iframe.loading = "lazy";
      iframe.referrerPolicy = "strict-origin-when-cross-origin";
      iframe.allowFullscreen = true;

      wrap.appendChild(iframe);
      mount.appendChild(wrap);
    });
  });
}
buildEmbeds();

// ---------- Modale LinkedIn ----------
const linkedinModal = document.getElementById("linkedinModal");
const openLinkedinBtn = document.getElementById("openLinkedin");

function openModal() {
  linkedinModal.classList.add("is-open");
  linkedinModal.setAttribute("aria-hidden", "false");
  document.body.classList.add("modal-open");
}
function closeModal() {
  linkedinModal.classList.remove("is-open");
  linkedinModal.setAttribute("aria-hidden", "true");
  document.body.classList.remove("modal-open");
}

if (openLinkedinBtn && linkedinModal) {
  openLinkedinBtn.addEventListener("click", openModal);
  linkedinModal.querySelectorAll("[data-close]").forEach((el) => {
    el.addEventListener("click", closeModal);
  });
  document.addEventListener("keydown", (e) => {
    if (e.key === "Escape" && linkedinModal.classList.contains("is-open")) {
      closeModal();
    }
  });
}

// ---------- Reveal on scroll ----------
const revealTargets = document.querySelectorAll(".hero__title, .hero__sub, .hero__cta, .about__title, .about__grid, .work__title, .project, .contact__title, .contact__sub, .contact__links");
revealTargets.forEach((el) => el.classList.add("reveal"));

const io = new IntersectionObserver(
  (entries) => {
    entries.forEach((entry) => {
      if (entry.isIntersecting) {
        entry.target.classList.add("is-visible");
        io.unobserve(entry.target);
      }
    });
  },
  { threshold: 0.12 }
);
revealTargets.forEach((el) => io.observe(el));
