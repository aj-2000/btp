<script>
  import Overview from "./overview/Overview.svelte";
  import RNNOverview from "./overview/RNNOverview.svelte";

  export let nn;

  // Enum to control the displaying view
  const View = {
    OVERVIEW: "overview",
    LAYERVIEW: "layerview",
    DETAILVIEW: "detailview",
  };

  let mainView = View.OVERVIEW;

  /* Example to read loaded cnn in other components:
  $: if ( $cnnStore.length != 0) {
    console.log($cnnStore);
  }
  */
</script>

<div id="explainer">
  <Overview />
</div>

<style>
  #explainer {
    width: 100%;
    padding: 0;
    margin: auto;
    outline: 1px solid var(--g-dark-gray);
  }
</style>
