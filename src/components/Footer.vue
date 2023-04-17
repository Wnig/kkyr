<template>
  <footer>
  	<div class="pc">
      <div class="left">
        <div class="con">
          <h2>厦门市佰中晟传媒有限公司</h2>
          <p>TEL：18206068856（林先生）<br/>
            ADD：厦门市思明区观音山商务营运中心18号4层    |    E-mail：kkyr@kkyrdt.com
          </p> 
          <p>闽ICP备18017748号-1</p>
        </div>
      </div>
  	</div>
  	<div class="mob">
      <div class="con">
        <div class="cons">
          <h2>厦门市佰中晟传媒有限公司</h2>
          <p>TEL：18206068856（林先生）</p>
          <p>ADD：厦门市思明区观音山商务营运中心18号4层</p>
          <p>E-mail：kkyr@kkyrdt.com</p>
          <p>闽ICP备18017748号-1</p> 
        </div>
      </div>
  	</div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	footer {
    height: 27.96vh;
    background: #323232;
  }
  .pc {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .left {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  h2 {
    margin-bottom: 1.94vh;
    font-family: PingFangSC-Light;
    font-size: 1.56vw;
    color: #FFFFFF;
    text-align: center;
  }
  p {
    font-family: PingFangSC-Regular;
    font-size: 1.04vw;
    color: #A7A7A7;
    line-height: 2.14vw;
    text-align: center;
  }
  

  

	@media screen and (max-width: 750px) {
    .pc {
      display: none;
    }
		.mob {
	    display: block;
	  }

    footer {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 22.49vh;
      background: #323232;
    }
    footer .con {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }
    h2 {
      text-align: center;
      margin-bottom: 1.95vh;
      font-size: 3.73vw;
      color: #FFFFFF;
    }
    p {
      text-align: center;
      font-size: 3.2vw;
      color: #A7A7A7;
      line-height: 5.87vw;
    }

	}

</style>
