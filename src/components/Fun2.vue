<script>
export default {
  functional: true,
  render(createElement) {
    return createElement("div", {
        staticClass: "x"
    }, [createElement("div", {
        staticClass: "y"
    }, ["second"]), createElement("div", {
        staticClass: "y"
    }, ["component"])])
  }
}
</script>
