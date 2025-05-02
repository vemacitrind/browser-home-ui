# Browser home-ui

A sleek, personalized browser start page with a live clock, greeting, and quick-access dashboard — built with Tailwind CSS.

![screenshot](preview.png)

##  Features

-  Real-time clock and day display
-  Quick-access dashboard with categorized links


## Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://github.com/vemacitrind/browser-home-ui.git

## Customize Your Own

Want to personalize it with your own links and profile? Just modify the card fields in the HTML.
  ```bash
    <div class="bg-gray-800 bg-opacity-70 rounded-lg p-4 shadow-md">
      <div class="text-slate-300 mb-4 flex items-center gap-2 justify-center">
        <span>
          <svg class="w-7 h-7 text-gray-800 dark:text-white" xmlns="http://www.w3.org/2000/svg" fill="none"
            viewBox="0 0 24 24">
            <!-- Your Icon SVG -->
          </svg>
        </span>
      </div>
      <ul class="space-y-2 text-slate-200 text-sm text-center mb-5">
        <li><a href="https://github.com/YOUR_USERNAME" target="_blank" class="font-bold text-base mb-1">Your Name</a></li>
        <li><a href="https://linkedin.com/in/YOUR_PROFILE" target="_blank" class="font-bold text-base mb-1">LinkedIn</a></li>
        <li><a href="https://chat.openai.com" target="_blank" class="font-bold text-base mb-1">ChatGPT</a></li>
        <li><a href="https://github.com/YOUR_USERNAME?tab=repositories" target="_blank" class="font-bold text-base">Repositories</a></li>
      </ul>
    </div>
