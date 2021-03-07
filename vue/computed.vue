
<script>
// computed
export default {
  data() {
    return {
      price: 100,
    };
  },
  computed: {
    doublePrice: {
      get() {
        return this.price * 2;
      },
      set(value) {
        this.price = value / 2;
      },
    },
  },
};
</script>