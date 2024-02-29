<script>
  import HyperparameterView from "../detail-view/Hyperparameterview.svelte";
  import Youtube from "./Youtube.svelte";

  let softmaxEquation = `$$\\text{Softmax}(x_{i}) = \\frac{\\exp(x_i)}{\\sum_j \\exp(x_j)}$$`;
  let reluEquation = `$$\\text{ReLU}(x) = \\max(0,x)$$`;

  let currentPlayer;
</script>

<body> </body>

<style>
  #description {
    margin-bottom: 60px;
    margin-left: auto;
    margin-right: auto;
    max-width: 78ch;
  }

  #description h2 {
    color: #444;
    font-size: 40px;
    font-weight: 450;
    margin-bottom: 12px;
    margin-top: 60px;
  }

  #description h4 {
    color: #444;
    font-size: 32px;
    font-weight: 450;
    margin-bottom: 8px;
    margin-top: 44px;
  }

  #description h6 {
    color: #444;
    font-size: 24px;
    font-weight: 450;
    margin-bottom: 8px;
    margin-top: 44px;
  }

  #description p {
    margin: 16px 0;
  }

  #description p img {
    vertical-align: middle;
  }

  #description .figure-caption {
    font-size: 13px;
    margin-top: 5px;
  }

  #description ol {
    margin-left: 40px;
  }

  #description p,
  #description div,
  #description li {
    color: #555;
    font-size: 17px;
    line-height: 1.6;
  }

  #description small {
    font-size: 12px;
  }

  #description ol li img {
    vertical-align: middle;
  }

  #description .video-link {
    color: #3273dc;
    cursor: pointer;
    font-weight: normal;
    text-decoration: none;
  }

  #description ul {
    list-style-type: disc;
    margin-top: -10px;
    margin-left: 40px;
    margin-bottom: 15px;
  }

  #description a:hover,
  #description .video-link:hover {
    text-decoration: underline;
  }

  .figure,
  .video {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
</style>
