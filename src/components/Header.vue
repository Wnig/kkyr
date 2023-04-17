<template>
  	<header>
	  	<div class="pc">
        <div class="cont">
          <a class="logo" @click="jump" ><img src="../assets/pclogo@3x.svg" alt=""></a>
          <ul class="nav">
            <!-- <li class="backstage"><a href="">后台登陆</a></li> -->
          </ul>
        </div>
	  	</div>
	  	<div class="mob">
        <div class="cont">
          <a class="logo" @click="jump" ><img src="../assets/pclogo@3x.svg" alt=""></a>
        </div>
	  	</div>
    </header>
</template>

<script>
let storage = window.sessionStorage;
export default {
  name: 'Header',
  data () {
    return {
    	navData: [
    		{tit: '首页', links:'/'},
        ],
      	num: '',
      	selShow: false
    }
  },
  created: function() {
    if(storage['selNumxinhongtu']) {
      this.num = storage['selNumxinhongtu'];
    } else {
      this.num = 0;
    };
  },
  methods: {
    selMenus(index) {
      storage['selNumxinhongtu'] = index;
      this.selShow = false;
    },
    isShow() {
      //点击：左侧菜单栏 收起-展开
      this.selShow = ! this.selShow;
    },
    jump() {
      storage['selNumxinhongtu'] = 0;
      this.selShow = false;
      this.$router.push({path: '/'});
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
  header {
    display: flex;
    justify-content: center;
    height: 12.36vw;
  }
  .pc {
    display: flex;
    width: 88%;
  }
  .cont {
    display: inline-flex;
    align-items: center;
    width: 100%;
  }
  .logo {
    width: 20.94vw;
    cursor: pointer;
  }
  .logo img {
    display: block;
    width: 100%;
  }

  .nav {
    flex: 1;
    display: flex;
    justify-content: flex-end;
  }
  .nav li {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .nav li a {
    font-family: PingFangSC-Regular;
    font-size: 1.56vw;
    color: #000000;
    text-align: center;
  }
  .nav .backstage {
    width: 11.25vw;
    height: 4.17vw;
    background: #FFFFFF;
    box-shadow: 0 2px 4px 0 rgba(0,0,0,0.09);
    border-radius: 100px;
  }


	
	@media screen and (max-width: 750px) {
		.pc {
			display: none;
		}
		.mob {
			display: flex;
			width: 85%;
		}

    header {
      display: flex;
      justify-content: center;
      height: 25.36vw;
    }
    .cont {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
    }
    .logo {
      width: 45.94vw;
      cursor: pointer;
    }
    .logo img {
      display: block;
      width: 100%;
    }

    .nav {
      flex: 1;
      display: flex;
      justify-content: flex-end;
    }
    .nav li {
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .nav li a {
      font-family: PingFangSC-Regular;
      font-size: 1.56vw;
      color: #FFFFFF;
    }
    .nav .backstage {
      width: 11.25vw;
      height: 4.17vw;
      background: #00C8B0;
      box-shadow: 0 5px 8px 0 rgba(0,0,0,0.20);
      border-radius: 100px;
    }

		
	}

	@media screen and (min-width: 751px) {
		
	}
</style>
