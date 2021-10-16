---
theme: default
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
---

# Cloud development with DrupalPod

## Drupal + DDev + Gitpod

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: image-right
image: https://s.gravatar.com/avatar/499831a65f45885a7e1b70ea47c06a58?s=800
---

<img class="h-10 absolute left-90" src="/images/logo-realityloop-logomark.png">

# Stuart Clark

<div class="my-10 grid grid-cols-[40px,1fr] w-min gap-y-4">
  <mdi-briefcase class="opacity-50" />
  <div><a href="https://www.realityloop.com" target="_blank">Realityloop.com</a></div>
  <mdi-drupal class="opacity-50" />
  <div><a href="https://www.drupal.org/u/Deciphered" target="_blank">Deciphered</a></div>
  <mdi-github class="opacity-50" />
  <div><a href="https://github.com/decipher" target="_blank">Decipher</a></div>
  <mdi-nuxt class="opacity-50" />
  <div><a href="https://druxtjs.org" target="_blank">DruxtJS.org</a></div>
  <mdi-earth class="opacity-50"/>
  <div>Australia</div>
</div>

<!--
Hello

I'm Stuart Clark:
* Senior Decoupled Developer @ Realityloop in Australia
* Drupal developer of 15 years
* Vue developer for 3/4 years
* Project lead of DruxtJS; a Decoupled Drupal framework for Nuxt.js

Today I'm talking about ...
-->

---
layout: section
---

<img src="/images/logo-drupalpod.png" class="m-auto block h-100" />

---
layout: section
---

# DrupalPod

https://drupalpod.com

## Start Drupal contributions with 1 click

1. Download the DrupalPod browser extension
Chrome or Firefox.

2. Go to any issue page on Drupal.org
(core, module, or theme).

3. Click on the DrupalPod extension.

4. (Optional) Choose a patch / issue fork / branch.

---
layout: section
---

# Demo

<video controls class="block w-3/4 m-auto">
  <source src="/videos/drupalpod.mp4" type="video/mp4" />
</video>

<!--
! Preprepare environment

https://www.drupal.org/project/drupal/issues/2942975
-->

---
layout: section
---

# DrupalPod4U

## Drupal + DDev + Gitpod

---
layout: section
---

# Getting started

<div class="text-left">

1. Install Drupal

```
composer create-project drupal/recommended-project [DESTINATION]
```

<div class="h-5" />

2. Install & configure DDev 4 Gitpod

```
brew install drud/ddev/ddev
ddev config global --omit-containers=ddev-router --instrumentation-opt-in=[BOOLEAN]
cd [DESTINATION] && ddev config
echo "bind_all_interfaces: true" >> .ddev/config.yaml
ddev start
```

<div class="h-5" />

3. Start

```
ddev start
```

</div>

---
background: /images/meme-someone_else.jpg
layout: cover
---

---
layout: section
---

# DrupalPod Stater-kit's

<div class="text-left mt-10">

- **drupalpod-starterkit**  
  Drupal 9 + DDev + Gitpod  
  http://github.com/drupalpod/drupalpod-starterkit

- **drupalpod-tome-starterkit**  
  Drupal 9 + Tome + DDev + Gitpod  
  http://github.com/drupalpod/drupalpod-tome-starterkit

- **quickstart-druxt-site**  
  Drupal 9 + DruxtJS + DDev + Gitpod  
  https://github.com/druxt/quickstart-druxt-site

</div>

---
layout: section
---

# Credits

<div class="grid grid-cols-[1fr,1fr] mt-10">
  <div class="m-auto">
    <img src="https://avatars.githubusercontent.com/u/22901?v=4" class="h-50 mb-5 rounded-full" />
    @shaal
  </div>
  <div class="m-auto">
    <img src="https://avatars.githubusercontent.com/u/112444?v=4"  class="h-50 mb-5 rounded-full" />
    @randyfay
  </div>
</div>
