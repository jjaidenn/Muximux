<script lang="ts">
  let { height, width, class: className = '' }: { height?: string; width?: string; class?: string } = $props();
</script>

<svg
  class={className}
  width={width || (height ? String(Math.round(Number(height) * 4)) : undefined)}
  height={height || (width ? String(Math.round(Number(width) / 4)) : '28')}
  viewBox="0 0 240 60"
  role="img"
  aria-label="BLVCK"
  xmlns="http://www.w3.org/2000/svg"
>
  <text x="120" y="43" text-anchor="middle" fill="currentColor"
    font-family="Arial, Helvetica, sans-serif" font-size="43"
    font-weight="800" letter-spacing="5">BLVCK</text>
  <path d="M24 53H216" stroke="#fb334f" stroke-width="3" stroke-linecap="round" />
</svg>
