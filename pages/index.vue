<template>
  <div class="relative">
    <!-- Hero Section -->
    <div class="relative isolate overflow-hidden animate-fade-in">
      <div class="mx-auto max-w-7xl px-6 pb-24 pt-10 sm:pb-32 lg:flex lg:px-8 lg:py-40">
        <div class="mx-auto max-w-2xl flex-shrink-0 lg:mx-0 lg:max-w-xl lg:pt-8">
          <div class="mt-24 sm:mt-32 lg:mt-16">
            <a href="/download" class="inline-flex space-x-6 animate-slide-down">
              <span class="rounded-full bg-orange-500/10 px-3 py-1 text-sm font-semibold leading-6 text-orange-400 ring-1 ring-inset ring-orange-500/20">
                Pre-release
              </span>
              <span class="inline-flex items-center space-x-2 text-sm font-medium leading-6 text-zinc-300">
                <span>v1.0.0-rc1</span>
                <svg class="h-5 w-5 text-zinc-500" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                  <path fill-rule="evenodd" d="M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z" clip-rule="evenodd" />
                </svg>
              </span>
            </a>
          </div>
          <h1 class="mt-10 text-4xl font-bold tracking-tight text-white sm:text-6xl font-display animate-slide-down delay-100">
            DesQTA - SEQTA Learn Desktop
          </h1>
          <p class="mt-6 text-lg leading-8 text-zinc-300 animate-fade-in delay-200">
            Experience SEQTA Learn like never before with our powerful desktop application,
            bringing the full SEQTA experience to your computer with enhanced features and performance.
          </p>
          <div class="mt-10 flex items-center gap-x-6 animate-fade-in delay-300">
            <NuxtLink
              href="/download"
              class="rounded-md bg-blue-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600 transition-all duration-200"
            >
              Download Now
              <ArrowDownTrayIcon class="ml-2 -mr-0.5 h-5 w-5 inline-block transition-transform duration-300 hover:scale-110" />
            </NuxtLink>
            <NuxtLink
              href="#features"
              class="text-sm font-semibold leading-6 text-white transition-colors duration-200 hover:text-blue-400"
            >
              Learn more <span aria-hidden="true">→</span>
            </NuxtLink>
          </div>
        </div>
      </div>
    </div>

    <!-- Feature Section -->
    <div id="features" class="py-24 sm:py-32 animate-fade-in delay-200">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class="mx-auto max-w-2xl lg:text-center">
          <h2 class="text-base font-semibold leading-7 text-blue-400 animate-slide-down">Enhanced Experience</h2>
          <p class="mt-2 text-3xl font-bold tracking-tight text-white sm:text-4xl animate-slide-down delay-100">
            Everything you need to succeed with SEQTA
          </p>
          <p class="mt-6 text-lg leading-8 text-zinc-300 animate-fade-in delay-200">
            DesQTA brings all the power of SEQTA Learn to your desktop, with additional features and improvements.
          </p>
        </div>
        <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-24 lg:max-w-none grid grid-cols-1 lg:grid-cols-3 gap-8">
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl p-8 flex flex-col items-start transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in">
            <dt class="flex items-center gap-x-3 text-base font-semibold leading-7 text-white">
              <ServerStackIcon class="h-7 w-7 flex-none text-blue-400 transition-transform duration-300 hover:scale-110" aria-hidden="true" />
              Enhanced Performance
            </dt>
            <dd class="mt-4 flex flex-auto flex-col text-base leading-7 text-zinc-300">
              <p class="flex-auto">Experience faster loading times and smoother interactions with our optimized desktop application.</p>
            </dd>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl p-8 flex flex-col items-start transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-100">
            <dt class="flex items-center gap-x-3 text-base font-semibold leading-7 text-white">
              <ShareIcon class="h-7 w-7 flex-none text-blue-400 transition-transform duration-300 hover:scale-110" aria-hidden="true" />
              Offline Access
            </dt>
            <dd class="mt-4 flex flex-auto flex-col text-base leading-7 text-zinc-300">
              <p class="flex-auto">Access your content even when you're offline, with automatic synchronization when you're back online.</p>
            </dd>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl p-8 flex flex-col items-start transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-200">
            <dt class="flex items-center gap-x-3 text-base font-semibold leading-7 text-white">
              <CursorArrowRaysIcon class="h-7 w-7 flex-none text-blue-400 transition-transform duration-300 hover:scale-110" aria-hidden="true" />
              Native Experience
            </dt>
            <dd class="mt-4 flex flex-auto flex-col text-base leading-7 text-zinc-300">
              <p class="flex-auto">Enjoy a native desktop experience with system integration and keyboard shortcuts.</p>
            </dd>
          </div>
        </div>
      </div>
    </div>

    <!-- Screenshots Section -->
    <div class="py-24 sm:py-32 animate-fade-in delay-200">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class="mx-auto max-w-2xl lg:text-center">
          <h2 class="text-base font-semibold leading-7 text-blue-400 animate-slide-down">Screenshots</h2>
          <p class="mt-2 text-3xl font-bold tracking-tight text-white sm:text-4xl animate-slide-down delay-100">
            See DesQTA in action
          </p>
          <p class="mt-6 text-lg leading-8 text-zinc-300 animate-fade-in delay-200">
            Take a look at some of the key features and interfaces of DesQTA.
          </p>
        </div>
        <div class="mt-16 grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in">
            <img src="/images/pics/home.png" alt="Home Dashboard" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Home Dashboard</h3>
              <p class="mt-2 text-zinc-300">Your personalized homepage with quick access to important information and upcoming tasks.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-100">
            <img src="/images/pics/home2.png" alt="Enhanced Home View" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Enhanced Home View</h3>
              <p class="mt-2 text-zinc-300">Customisable home layout with comprehensive overview of your academic progress and notifications.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-200">
            <img src="/images/pics/assement.png" alt="Assessments Management" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Assessments</h3>
              <p class="mt-2 text-zinc-300">Comprehensive assessment tracking with detailed information, due dates, and submission status.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-200">
            <img src="/images/pics/courses(1).png" alt="Course Management" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Course Management</h3>
              <p class="mt-2 text-zinc-300">Access all your courses, learning materials, and resources in an organized, easy-to-navigate interface.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in">
            <img src="/images/pics/dm (1).png" alt="Direct Messages" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Direct Messages</h3>
              <p class="mt-2 text-zinc-300">Stay connected with teachers and classmates through the integrated messaging system with real-time notifications.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-100">
            <img src="/images/pics/news.png" alt="News & Updates" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">News & Updates</h3>
              <p class="mt-2 text-zinc-300">Stay informed with the latest news and important updates from around the world in a clean, readable format.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-200">
            <img src="/images/pics/notices.png" alt="Notices & Announcements" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Notices & Announcements</h3>
              <p class="mt-2 text-zinc-300">Important notices and announcements from teachers and administration, organized for easy access.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in">
            <img src="/images/pics/timetable1(1).png" alt="Class Timetable" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Class Timetable</h3>
              <p class="mt-2 text-zinc-300">View your weekly schedule, class times, and room locations in an intuitive timetable interface.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-100">
            <img src="/images/pics/grade-report.png" alt="Grade Reports" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Grade Reports</h3>
              <p class="mt-2 text-zinc-300">Track your academic progress with detailed grade reports and performance analytics.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-200">
            <img src="/images/pics/reports.png" alt="Academic Reports" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Academic Reports</h3>
              <p class="mt-2 text-zinc-300">Comprehensive academic reports with detailed insights into your learning progress and achievements from your school.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in">
            <img src="/images/pics/schooldirectory.png" alt="School Directory" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">School Directory</h3>
              <p class="mt-2 text-zinc-300">Access information about your fellow students through the comprehensive school directory.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-100">
            <img src="/images/pics/settings.png" alt="Application Settings" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Application Settings</h3>
              <p class="mt-2 text-zinc-300">Customize your DesQTA experience with comprehensive settings for notifications, appearance, and preferences.</p>
            </div>
          </div>
          <div class="backdrop-blur-lg bg-white/5 border border-white/10 rounded-2xl shadow-xl overflow-hidden transition-transform duration-300 hover:-translate-y-2 hover:shadow-2xl animate-fade-in delay-200">
            <img src="/images/pics/themes(1).png" alt="Theme Customization" class="w-full h-auto object-cover" />
            <div class="p-6">
              <h3 class="text-lg font-semibold text-white">Theme Customization</h3>
              <p class="mt-2 text-zinc-300">Personalize your interface with multiple theme options and customization settings for a comfortable viewing experience.</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- CTA Section -->
    <div class="relative isolate mt-32 px-6 py-32 sm:mt-56 sm:py-40 lg:px-8 animate-fade-in delay-300">
      <svg class="absolute inset-0 -z-10 h-full w-full stroke-zinc-200 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
        <defs>
          <pattern id="1d4240dd-898f-445f-932d-e2872fd12de3" width="200" height="200" x="50%" y="0" patternUnits="userSpaceOnUse">
            <path d="M.5 200V.5H200" fill="none" />
          </pattern>
        </defs>
        <svg x="50%" y="0" class="overflow-visible fill-zinc-800">
          <path d="M-200 0h201v201h-201Z M600 0h201v201h-201Z M-400 600h201v201h-201Z M200 800h201v201h-201Z" stroke-width="0" />
        </svg>
        <rect width="100%" height="100%" stroke-width="0" fill="url(#1d4240dd-898f-445f-932d-e2872fd12de3)" />
      </svg>
      <div class="mx-auto max-w-2xl text-center">
        <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl animate-slide-down">Ready to get started?<br>Download DesQTA today.</h2>
        <p class="mx-auto mt-6 max-w-xl text-lg leading-8 text-zinc-300 animate-fade-in delay-100">
          Join thousands of students and teachers who are already using DesQTA to enhance their SEQTA Learn experience.
        </p>
        <div class="mt-10 flex items-center justify-center gap-x-6 animate-fade-in delay-200">
          <NuxtLink
            href="/download"
            class="rounded-md bg-blue-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600 transition-all duration-200"
          >
            Download Now
          </NuxtLink>
          <NuxtLink href="/comparison" class="text-sm font-semibold leading-6 text-white transition-colors duration-200 hover:text-blue-400">
            Learn more <span aria-hidden="true">→</span>
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import {
  ServerStackIcon,
  ShareIcon,
  CursorArrowRaysIcon,
  ArrowDownTrayIcon,
} from "@heroicons/vue/24/outline";

useHead({
  title: "Home",
});
</script>

<style scoped>
@keyframes fade-in {
  from { opacity: 0; transform: translateY(24px); }
  to { opacity: 1; transform: none; }
}
@keyframes slide-down {
  from { opacity: 0; transform: translateY(-24px); }
  to { opacity: 1; transform: none; }
}
.animate-fade-in {
  animation: fade-in 0.8s cubic-bezier(0.4,0,0.2,1) both;
}
.animate-slide-down {
  animation: slide-down 0.8s cubic-bezier(0.4,0,0.2,1) both;
}
.delay-100 { animation-delay: 0.1s; }
.delay-200 { animation-delay: 0.2s; }
.delay-300 { animation-delay: 0.3s; }
</style>