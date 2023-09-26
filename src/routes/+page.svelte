<script>
  import { InferenceSession } from 'onnxruntime-web'
  import { onMount } from 'svelte'

  onMount(() => {
    const session = InferenceSession.create('sam_onnx_quantized.onnx')
  })
</script>

<a href="/app">/app</a>
