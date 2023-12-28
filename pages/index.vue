<template>
  <section class="section">
    <b-title></b-title>
    <div class="columns is-mobile">
      <card title="お問い合わせ" icon="mail"> ご連絡お待ちしております。 </card>
    </div>
  </section>
</template>

<script>
import Card from '~/components/Card'

export default {
  name: 'IndexPage',
  components: {
    Card,
  },
}
</script>
