<template>
  <p class="m-10 text-center text-sm text-gray-400 dark:text-neutral-400">
    {{ $t('client.empty') }}<br /><br />
    <ClientsCreateDialog>
      <BaseButton as="span">
        <IconsPlus class="w-4 md:mr-2" />
        <span class="text-sm">{{ $t('client.new') }}</span>
      </BaseButton>
    </ClientsCreateDialog>
  </p>
</template>
