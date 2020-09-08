<script>
  import { Router } from '@sveltech/routify';
  import { routes } from '../.routify/routes';

  import '../node_modules/uikit/dist/js/uikit.js';
  import '../node_modules/uikit/dist/js/uikit-icons.js';
</script>

<Router routes="{routes}" />

<style lang="scss" global>
  @import '../node_modules/uikit/src/scss/mixins-theme.scss';
  @import '../node_modules/uikit/src/scss/mixins.scss';
  @import '../node_modules/uikit/src/scss/variables-theme.scss';
  @import '../node_modules/uikit/src/scss/variables.scss';
  @import '../node_modules/uikit/src/scss/uikit.scss';

  .abcdefg {
    color: red;

    .xyz {
      color: blue;

      .cccc {
        color: cyan;
      }
    }
  }
</style>
