<template>
  <PageWrapper class="flex flex-col justify-center items-center">
    <PageHeader>
      <PageTitle :text="$t('pages.about.title')" class="capitalize" />
    </PageHeader>
    <PageBody>
      <div class="flex flex-col items-center">
        <img
          src="https://avatars.githubusercontent.com/u/80070502?v=4"
          class="inline-block rounded-full"
          alt="guard"
          width="100"
          height="100"
        />
        <Button
          size="xs"
          text="Guard"
          class="font-extrabold mt-4"
          href="https://github.com/guardscripts"
        />
      </div>
    </PageBody>
  </PageWrapper>
</template>

<script lang="ts" setup>
definePageMeta({
  layout: 'page',
})
</script>
