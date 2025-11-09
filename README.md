<!DOCTYPE html>

<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Profile Page - Learn.TV</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Lexend:wght@100..900&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet"/>
<script>
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "primary": "#137fec",
              "background-light": "#f6f7f8",
              "background-dark": "#101922",
            },
            fontFamily: {
              "display": ["Lexend"]
            },
            borderRadius: {"DEFAULT": "1rem", "lg": "2rem", "xl": "3rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
        body {
            font-family: 'Lexend', sans-serif;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background-light dark:bg-background-dark font-display">
<div class="relative flex min-h-screen w-full flex-col group/design-root overflow-x-hidden">
<!-- Top App Bar -->
<div class="flex items-center bg-transparent p-4 pb-2 justify-between sticky top-0 z-10 bg-background-light dark:bg-background-dark">
<div class="text-[#111418] dark:text-white flex size-12 shrink-0 items-center justify-center">
<span class="material-symbols-outlined text-2xl">arrow_back</span>
</div>
<h2 class="text-[#111418] dark:text-white text-lg font-bold leading-tight tracking-[-0.015em] flex-1 text-center -ml-12">Profile</h2>
</div>
<div class="flex flex-col flex-grow p-4">
<!-- Main Content Card -->
<div class="flex w-full flex-col items-center gap-6 rounded-xl bg-white dark:bg-[#1C2A3A] p-6 shadow-[0_4px_12px_rgba(0,0,0,0.05)] dark:shadow-[0_4px_20px_rgba(0,0,0,0.2)]">
<!-- Profile Header -->
<div class="flex flex-col gap-4 items-center">
<div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full h-32 w-32 border-4 border-white dark:border-[#1C2A3A] shadow-md" data-alt="Profile picture of Razi Student" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuAmbmweKhgmQF31x-ChiExY9zMGLpAFLBs76kV8tE0t0P0_HVNqbqle_Hny9LsCEO3C_BY5yMWZmS4FXtKRRrAptJPhINEm8pj47qERCFwiqcBn-Ira-zw9YiLtpMVNNP0qeXFDfZnsXzBcgJLuBI_lKDnBAvadz7HlFHdyhNu9gSFZhqbagTZeTSVX2wcxd8reZ1eXwIqrBTHxDdL5JZjqsHGvQ50YXt6LzsO0V--jiJx5dxCsR8LUfoCCp0_ld_oijV9FnLlKq-Iw");'></div>
<div class="flex flex-col items-center justify-center">
<p class="text-[#343A40] dark:text-white text-[22px] font-bold leading-tight tracking-[-0.015em] text-center">Student</p>
<p class="text-[#6C757D] dark:text-gray-400 text-base font-normal leading-normal text-center">babajox.student@email.com</p>
</div>
</div>
<!-- Edit Profile Button -->
<div class="w-full">
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 px-5 flex-1 w-full bg-[#A0D2EB] text-[#343A40] text-base font-bold leading-normal tracking-[0.015em] hover:bg-opacity-90 transition-colors">
<span class="truncate">Edit Profile</span>
</button>
</div>
</div>
<!-- Spacer -->
<div class="flex-grow"></div>
<!-- Logout Button -->
<div class="flex py-3 w-full mt-6">
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 px-5 flex-1 bg-[#E63946] bg-opacity-10 dark:bg-opacity-20 text-[#E63946] text-base font-bold leading-normal tracking-[0.015em] hover:bg-opacity-20 dark:hover:bg-opacity-30 transition-colors">
<span class="truncate">Logout</span>
</button>
</div>
</div>
</div>
</body></html>
