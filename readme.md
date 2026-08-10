 <style>
    :root {
      --primary: #ededed;
      --secondary: #cfcfcf;
      --dim: #cfcfcf;
      --accent: #cfcfcf;
    }

    .mono {
      font-family: "General Sans";
    }

    .secondary-font {
      font-family:
        ui-monospace,
        "SFMono-Regular",
        "SF Mono",
        Menlo,
        Consolas,
        "Liberation Mono",
        monospace;
    }

    .link{
      font-family: "General Sans";
      font-size: 15px;
      text-decoration: underline;
      color: var(--primary);
      margin-inline: 5px;
    }

    .draw {
      stroke-dasharray: 1000;
      stroke-dashoffset: 1000;
      animation: draw 1.4s cubic-bezier(.6, 0, .2, 1) forwards;
    }

    @keyframes draw {
      to {
        stroke-dashoffset: 0;
      }
    }

    .rise {
      opacity: 0;
      animation: rise .9s cubic-bezier(.2, .7, .2, 1) forwards;
    }

    @keyframes rise {
      from {
        opacity: 0;
        transform: translateY(12px);
      }

      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .fade {
      opacity: 0;
      animation: fade .7s ease forwards;
    }

    @keyframes fade {
      to {
        opacity: 1;
      }
    }

    .a1 {
      animation-delay: .2s;
    }

    .a2 {
      animation-delay: .5s;
    }

    .a3 {
      animation-delay: .9s;
    }

    .a4 {
      animation-delay: 1.2s;
    }

    .a5 {
      animation-delay: 1.5s;
    }

    .a6 {
      animation-delay: 1.8s;
    }

    @media (prefers-reduced-motion: reduce) {

      .draw,
      .rise,
      .fade {
        animation: none;
      }

      .draw {
        stroke-dashoffset: 0;
      }

      .rise,
      .fade {
        opacity: 1;
      }
    }
  </style>

<div align="center">
<picture><img src="/assests/header-v1.svg" alt="Muhammad Jawad"/></picture>

<a href="https://jawad.studio" class='link' >
    Jawad.studio
</a>
<a href="https://www.linkedin.com/in/jawad-studio" class='link'>
    LinkedIn
</a>
<a href="mailto:[contact@jawad.studio]" class='link' >
contact@jawad.studio
</a>

</div>

<picture><img src="/assests/about.svg" alt="About Jawad"/></picture>

<picture><img src="/assests/works.svg" alt="Selected Works"/></picture>
