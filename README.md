<style>
* {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

div.container {
  width: 80%;
  margin: 0 auto;
  text-align: center;
}

.b-header {
  margin-bottom: 6rem;
}

a {
  text-decoration: none;
  color: #2c292d;
}

.b-header__logo {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' viewBox='0 0 512 512'%3e%3cdefs%3e%3clinearGradient id='a' x1='370' y1='58.546' x2='142' y2='453.454' gradientUnits='userSpaceOnUse'%3e%3cstop offset='0' stop-color='%23222'/%3e%3cstop offset='1' stop-color='%23111'/%3e%3c/linearGradient%3e%3clinearGradient id='b' x1='370' y1='58.546' x2='142' y2='453.454' gradientUnits='userSpaceOnUse'%3e%3cstop offset='0' stop-color='%23ffd966'/%3e%3cstop offset='0.5' stop-color='%23ff9059'/%3e%3cstop offset='1' stop-color='%23ff6188'/%3e%3c/linearGradient%3e%3clinearGradient id='d' x1='316' y1='147.97' x2='196' y2='355.816' xlink:href='%23b'/%3e%3c/defs%3e%3ctitle%3eapp-icon%3c/title%3e%3cpath d='M484%2c350.685V161.315a64%2c64%2c0%2c0%2c0-32-55.426L288%2c11.2a64%2c64%2c0%2c0%2c0-64%2c0L60%2c105.889a64%2c64%2c0%2c0%2c0-32%2c55.426v189.37a64%2c64%2c0%2c0%2c0%2c32%2c55.426L224%2c500.8a64%2c64%2c0%2c0%2c0%2c64%2c0l164-94.686A64%2c64%2c0%2c0%2c0%2c484%2c350.685Z' fill='url(%23a)'/%3e%3cpath d='M256%2c26.629a40.051%2c40.051%2c0%2c0%2c1%2c20%2c5.359l164%2c94.686a40.111%2c40.111%2c0%2c0%2c1%2c20%2c34.64V350.685a40.114%2c40.114%2c0%2c0%2c1-20%2c34.642L276%2c480.012a40%2c40%2c0%2c0%2c1-40%2c0L72%2c385.327a40.114%2c40.114%2c0%2c0%2c1-20-34.642V161.314a40.111%2c40.111%2c0%2c0%2c1%2c20-34.64L236%2c31.988a40.051%2c40.051%2c0%2c0%2c1%2c20-5.359m0-24A63.96%2c63.96%2c0%2c0%2c0%2c224%2c11.2L60%2c105.889a64%2c64%2c0%2c0%2c0-32%2c55.425V350.685a64%2c64%2c0%2c0%2c0%2c32%2c55.426L224%2c500.8a64%2c64%2c0%2c0%2c0%2c64%2c0l164-94.686a64%2c64%2c0%2c0%2c0%2c32-55.426V161.314a64%2c64%2c0%2c0%2c0-32-55.425L288%2c11.2a63.96%2c63.96%2c0%2c0%2c0-32-8.574Z' fill='url(%23b)'/%3e%3cpath d='M256%2c14.629A52.067%2c52.067%2c0%2c0%2c1%2c282%2c21.6l164%2c94.685a52.145%2c52.145%2c0%2c0%2c1%2c26%2c45.034v189.37a52.145%2c52.145%2c0%2c0%2c1-26%2c45.034L282%2c490.4a52%2c52%2c0%2c0%2c1-52%2c0L66%2c395.719a52.145%2c52.145%2c0%2c0%2c1-26-45.034V161.315a52.145%2c52.145%2c0%2c0%2c1%2c26-45.034L230%2c21.6a52.067%2c52.067%2c0%2c0%2c1%2c26-6.967m0-12A63.96%2c63.96%2c0%2c0%2c0%2c224%2c11.2L60%2c105.889a64%2c64%2c0%2c0%2c0-32%2c55.426v189.37a64%2c64%2c0%2c0%2c0%2c32%2c55.426L224%2c500.8a64%2c64%2c0%2c0%2c0%2c64%2c0l164-94.686a64%2c64%2c0%2c0%2c0%2c32-55.426V161.315a64%2c64%2c0%2c0%2c0-32-55.426L288%2c11.2a63.96%2c63.96%2c0%2c0%2c0-32-8.574Z' fill='url(%23a)'/%3e%3cpath d='M308%2c152.589%2c260%2c180.3a8%2c8%2c0%2c0%2c1-8%2c0l-48-27.713a16%2c16%2c0%2c0%2c0-16%2c0l-44%2c25.4a16%2c16%2c0%2c0%2c0-8%2c13.857V311.938a16%2c16%2c0%2c0%2c0%2c8%2c13.856l52%2c30.022%2c9%2c5.2a4%2c4%2c0%2c0%2c0%2c6-3.464v-47a8%2c8%2c0%2c0%2c0-2.387-5.7l-45.38-44.683a2%2c2%2c0%2c0%2c1%2c2.4-3.157L211%2c283.2l41%2c23.671a8%2c8%2c0%2c0%2c0%2c8%2c0L301%2c283.2%2c346.363%2c257a2%2c2%2c0%2c0%2c1%2c2.4%2c3.157l-45.38%2c44.683a8%2c8%2c0%2c0%2c0-2.387%2c5.7v47a4%2c4%2c0%2c0%2c0%2c6%2c3.464l9-5.2%2c52-30.022a16%2c16%2c0%2c0%2c0%2c8-13.856V191.849a16%2c16%2c0%2c0%2c0-8-13.857l-44-25.4A16%2c16%2c0%2c0%2c0%2c308%2c152.589Z' fill='url(%23d)'/%3e%3c/svg%3e");
  background-repeat: no-repeat;
  background-position: center;
  background-size: contain;
  width: 12rem;
  height: 12rem;
  margin: 2rem auto 0;
}

.b-header h1 {
  font-size: 3rem;
  color: #ccc;
  font-weight: 500;
  line-height: 1;
  margin: 2rem auto 1rem;
}

.b-header h2 {
    color: #777;
  margin: 0 auto 3rem;
  font-weight: 400;
  font-size: 1rem;
  text-transform: uppercase;
  line-height: 1;
  letter-spacing: 0.05em;
}
</style>
<body>
<div class="container">
<div class="b-header">
  <a class="active" href="https://monokai.pro/">
    <div class="b-header__logo"></div>
    <h1>Monokai Pro</h1>
    <h2>Beautiful functionality for professional developers</h2>
  </a>
</div>
</div>
</body>
