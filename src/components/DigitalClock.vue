<template>
  <div>
    <div>
      <p>
        {{ currentTime.toLocaleTimeString() }}
      </p>
      <p>
        {{ currentTime.toLocaleDateString() }}
      </p>
    </div>
  </div>
</template>
<script type="module">
import { useCurrentTime } from "@/Composables/useCurrentTime";
export default {
  name: "CurrentTimeExample",

  setup() {
    const { currentTime } = useCurrentTime();
    console.log(currentTime.value);
    return { currentTime };
  },
};
</script>
