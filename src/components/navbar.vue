<template>
  <div class="nav">
     <vk-navbar >
      <vk-navbar-nav>
        <vk-navbar-logo class="animated infinite bounce">{{brand}}</vk-navbar-logo>
      </vk-navbar-nav>

        <vk-navbar-nav slot = "right" class = "uk-visible@m">
            <vk-navbar-nav-item icon="" title="Home"></vk-navbar-nav-item>
             <vk-navbar-nav-item icon="" title="Dashboard"></vk-navbar-nav-item>
             <vk-navbar-nav-item icon="" title="Accounts"></vk-navbar-nav-item>
            
        </vk-navbar-nav>
        <vk-navbar-nav slot ="right" class = "uk-hidden@m">
             <vk-navbar-toggle  title="MENU" class="animated infinite bounce"></vk-navbar-toggle>
        </vk-navbar-nav>
        
    </vk-navbar>

   </div>
</template>

<script>


export default {

data(){
return{
  
  brand:'Wecycler',

  }
}

}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">

@import '../../node_modules/uikit/src/less/uikit.less';



@navbar-background:linear-gradient(45deg,#F32F8E,#B236D0);
@navbar-nav-item-color: white;
@navbar-item-color: white;
@navbar-nav-item-active-color: white;
@navbar-nav-item-hover-color:  white;
@navbar-nav-item-onclick-color:  white;
@navbar-toggle-color:  white;
@navbar-toggle-hover-color: white;
@navbar-nav-item-padding-horizontal: 10px;
@navbar-nav-item-font-size: auto;
@navbar-nav-item-height: 40px;
@navbar-nav-item-font-family:'Sigmar One', cursive;

@logo-color:white;
@logo-hover-color:white;
@logo-font-family:'Orbitron', sans-serif;
@logo-font-size: auto;


</style>