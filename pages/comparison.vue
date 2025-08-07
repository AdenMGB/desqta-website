<template>
  <div class="relative isolate overflow-hidden">
    <div class="mx-auto max-w-5xl px-6 py-24 sm:py-32 lg:px-8 animate-fade-in">
      <div class="mx-auto max-w-2xl text-center">
        <h2 class="text-base font-semibold leading-7 text-blue-400 animate-slide-down">Feature Comparison</h2>
        <p class="mt-2 text-3xl font-bold tracking-tight text-white sm:text-4xl animate-slide-down delay-100">
          DesQTA vs Web Version
        </p>
        <p class="mt-6 text-lg leading-8 text-zinc-300 animate-fade-in delay-200">
          See how DesQTA stacks up against the web version of SEQTA Learn.
        </p>
      </div>
      <div class="mt-16 overflow-x-auto">
        <table class="w-full text-left rounded-2xl bg-white/5 shadow-xl">
          <thead>
            <tr>
              <th class="px-6 py-4 text-lg font-semibold text-white">Feature</th>
              <th class="px-6 py-4 text-lg font-semibold text-blue-400 text-center">DesQTA</th>
              <th class="px-6 py-4 text-lg font-semibold text-zinc-300 text-center">Web Version</th>
            </tr>
          </thead>
          <tbody class="divide-y divide-white/10 rounded-2xl">
            <!-- Organise so features both software have come first -->
            <!-- <Checkmark /> for yes, <Crossmark /> for no, <Semimark /> for somewhat -->
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Better than default SEQTA</td>
              <td class="px-6 py-5 text-center align-middle"><Checkmark /></td>
              <td class="px-6 py-5 text-center align-middle"><Checkmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Grades calculator</td>
              <td class="px-6 py-5 text-center align-middle"><Checkmark /></td>
              <td class="px-6 py-5 text-center align-middle"><Checkmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Global search</td>
              <td class="px-6 py-5 text-center align-middle"><Checkmark /></td>
              <td class="px-6 py-5 text-center align-middle"><Checkmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Custom home page</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Semimark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Modern, responsive interface</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Semimark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Local notifications</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Semimark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Local application</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Works whilst offline</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Enhanced styling editor</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Optimised performance</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Full system integration</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Browser independent</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">RSS news feeds</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Cloud-based messaging</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Cloud settings sync</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">AI integration & features</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">To Do list</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Focus timer</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
            <tr>
              <td class="px-6 py-5 text-base text-zinc-300">Student directory</td>
              <td class="px-6 py-5 text-center"><Checkmark /></td>
              <td class="px-6 py-5 text-center"><Crossmark /></td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="mx-auto mt-32 max-w-2xl text-center animate-fade-in delay-400">
        <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl animate-slide-down">Ready to try DesQTA?</h2>
        <p class="mt-6 text-lg leading-8 text-zinc-300 animate-fade-in delay-100">
          Download DesQTA today and see the difference for yourself.
        </p>
        <div class="mt-10 flex items-center justify-center gap-x-6 animate-fade-in delay-200">
          <NuxtLink
            href="/download"
            class="rounded-md bg-blue-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600 transition-all duration-200"
          >
            Download now
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
// Simple checkmark and crossmark SVG components
const Checkmark = defineComponent({
  name: 'Checkmark',
  template: `
    <svg fill="#fff" width="24px" height="24px" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg" class="mx-auto">
      <path d="M16,.5C7.44.5.5,7.44.5,16s6.94,15.5,15.5,15.5,15.5-6.94,15.5-15.5S24.56.5,16,.5Z"/>
    </svg>
  `
})

const Crossmark = defineComponent({
  name: 'Crossmark',
  template: `
    <svg fill="#e6e7e8" width="24px" height="24px" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg" class="mx-auto">
      <path d="M16,.5C7.44.5.5,7.44.5,16s6.94,15.5,15.5,15.5,15.5-6.94,15.5-15.5S24.56.5,16,.5ZM16,30.5c-8.01,0-14.5-6.49-14.5-14.5S7.99,1.5,16,1.5s14.5,6.49,14.5,14.5-6.49,14.5-14.5,14.5Z"></path>
    </svg>
  `
})

const Semimark = defineComponent({
  name: 'Semimark',
  template: `
    <svg fill="#f1f2f2" width="24px" height="24px" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg" class="mx-auto">
      <path d="M16,.5C7.44.5.5,7.44.5,16s6.94,15.5,15.5,15.5,15.5-6.94,15.5-15.5S24.56.5,16,.5ZM16,1.5c8.01,0,14.5,6.49,14.5,14.5s-6.49,14.5-14.5,14.5"/>
    </svg>
  `
})

useHead({
  title: "Comparison",
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
.delay-400 { animation-delay: 0.4s; }
</style>
