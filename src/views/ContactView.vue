<template>
  <div class="w-min text-center">
    <SectionTitle>Contact Me</SectionTitle>

    <div class="mt-24 flex flex-col justify-center gap-6 transition-all">
      <ContactItem
        classs="text-red-400"
        :path="mdiGmail"
        text="anwiwah@gmail.com"
        href="mailto:anwiwah@gmail.com"
      />
      <ContactItem
        classs="text-dark-700 dark:text-slate-200"
        :path="mdiGithub"
        text="anwiwah"
        href="https://github.com/anwiwah"
      />
      <ContactItem
        classs="text-violet-400"
        :path="mdiInstagram"
        text="@anwiwah"
        href="https://instagram.com/anwiwah__"
      />
      <ContactItem
        classs="text-blue-400"
        :path="mdiSend"
        text="@anwiwah"
        href="https://t.me/anwiwah"
      />
    </div>

    <h6 class="mt-24 text-sm opacity-50">2023 © Andi wira waHyudi</h6>
  </div>
</template>

<script setup lang="ts">
import ContactItem from "@/components/ContactItem.vue";
import SectionTitle from "@/components/SectionTitle.vue";
import { mdiGmail, mdiGithub, mdiInstagram, mdiSend } from "@mdi/js";
</script>
