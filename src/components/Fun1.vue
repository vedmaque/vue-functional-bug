<script>
export default {
  functional: true,
  render(createElement) {
    return createElement("div", {
        staticClass: "a"
    }, [createElement("div", {
        staticClass: "b"
    }, ["first"]), createElement("div", {
        staticClass: "b"
    }, ["component"])])
  }
}
</script>
