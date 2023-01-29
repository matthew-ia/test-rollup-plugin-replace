<script>
  import getFoo from './foo.js';
</script>

<p>This gets replaced: @FOO</p>
<p>This does get replaced in Rollup: {getFoo()}</p>