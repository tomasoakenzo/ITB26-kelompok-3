// Mengatur buka-tutup menu navigasi mobile (hamburger menu)

// 1. Ambil elemen tombol menu dan kontainer navigasi
const navToggle = document.getElementById('navToggle');
const siteNav = document.getElementById('siteNav');

// 2. Fungsi buka/tutup menu saat tombol ikon 3 garis diklik
navToggle.addEventListener('click', () => {
  const isOpen = siteNav.classList.toggle('is-open');
  navToggle.setAttribute('aria-expanded', isOpen ? 'true' : 'false');
});

// 3. Fungsi otomatis menutup menu kembali jika salah satu link di dalamnya diklik
document.querySelectorAll('.site-nav a').forEach((link) => {
  link.addEventListener('click', () => {
    siteNav.classList.remove('is-open');
    navToggle.setAttribute('aria-expanded', 'false');
  });
});
