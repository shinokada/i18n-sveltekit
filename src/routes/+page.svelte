<script>
  import { i, language } from '@inlang/sdk-js'
  console.log(language) // => e.g 'en'
  let company = 'Flowbite-Svelte'
  let name = 'FS'
  let costumer = 'Customer'
</script>

<h1>{i('intro')}</h1>

<p>
  {i('button')}
</p>
<p>
  {i('logout.title')}
</p>
<p>
  {i('variable-test')}
</p>