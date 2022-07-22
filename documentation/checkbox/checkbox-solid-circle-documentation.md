---
state:
  options: 'Option 2'
---

### Solid circle

Vuero checkboxes can be circles instead of squares. Simply add the `circle`
attribute to your checkbox element.
See the code example for more details about usage.

<!--code-->

```vue
<script setup lang="ts">
import { ref } from 'vue'

const options = ref('Option 2')
</script>

<template>
  <VField class="is-flex">
    <VControl raw subcontrol>
      <VCheckbox v-model="options" true-value="Option 1" label="Option 1" solid circle />
    </VControl>
    <VControl raw subcontrol>
      <VCheckbox
        v-model="options"
        true-value="Option 2"
        label="Option 2"
        color="primary"
        solid
        circle
      />
    </VControl>
    <VControl raw subcontrol>
      <VCheckbox
        v-model="options"
        true-value="Option 3"
        label="Option 3"
        color="info"
        solid
        circle
      />
    </VControl>
    <VControl raw subcontrol>
      <VCheckbox
        v-model="options"
        true-value="Option 4"
        label="Option 4"
        color="success"
        solid
        circle
      />
    </VControl>
    <VControl raw subcontrol>
      <VCheckbox
        v-model="options"
        true-value="Option 5"
        label="Option 5"
        color="warning"
        solid
        circle
      />
    </VControl>
    <VControl raw subcontrol>
      <VCheckbox
        v-model="options"
        true-value="Option 6"
        label="Option 6"
        color="danger"
        solid
        circle
      />
    </VControl>
  </VField>
</template>
```

<!--/code-->

<!--example-->

<VField class="is-flex">
  <VControl raw subcontrol>
    <VCheckbox
      v-model="frontmatter.state.options"
      trueValue="Option 1"
      label="Option 1"
      solid
      circle
    />
  </VControl>
  <VControl raw subcontrol>
    <VCheckbox
      v-model="frontmatter.state.options"
      trueValue="Option 2"
      label="Option 2"
      color="primary"
      solid
      circle
    />
  </VControl>
  <VControl raw subcontrol>
    <VCheckbox
      v-model="frontmatter.state.options"
      trueValue="Option 3"
      label="Option 3"
      color="info"
      solid
      circle
    />
  </VControl>
  <VControl raw subcontrol>
    <VCheckbox
      v-model="frontmatter.state.options"
      trueValue="Option 4"
      label="Option 4"
      color="success"
      solid
      circle
    />
  </VControl>
  <VControl raw subcontrol>
    <VCheckbox
      v-model="frontmatter.state.options"
      trueValue="Option 5"
      label="Option 5"
      color="warning"
      solid
      circle
    />
  </VControl>
  <VControl raw subcontrol>
    <VCheckbox
      v-model="frontmatter.state.options"
      trueValue="Option 6"
      label="Option 6"
      color="danger"
      solid
      circle
    />
  </VControl>
</VField>

<!--/example-->
