<template>
  <q-page class="q-pr-lg q-pl-lg q-pt-none q-mt-none">
    
    <div class="row q-ma-none q-pa-a-none">
        
      <div class="col-xs-12 col-sm-6 col-md-6 text-center">
          <q-header class="style-header">
            <div class="q-pa-xm q-ma-xm styleDiv">
              <div class="q-gutter-y-xm column">
                <q-toolbar class="bg-primary styleToolbar text-black rounded-borders">
                  <div class="row">
                    <q-btn round dense flat icon="menu" class="q-mr-xs" />
                    <h5 class="title">Programms</h5>
                  </div>
                  <q-list class="row">
                     <q-item>courses</q-item>  
                     <q-item>features</q-item>  
                     <q-item>support</q-item>  
                  </q-list>
                  
                  <div>
                    <q-btn flat round dense icon="email">
                      <q-badge floating color="red">2</q-badge>
                    </q-btn>
                    <q-avatar class="gt-xs">
                      <img src="statics/makant.jpg">
                    </q-avatar>
                  </div>

                 
                </q-toolbar>
              </div>
            </div>
          </q-header>
          <div class="content-body">
              <h4 class="q-ma-xm q-pa-none">Study 3 different areas of web design easily in 3 Steps</h4>
              <ul class="list-style">
                  <li><span class="span-num">.01</span> Visit our website</li>
                  <li><span class="span-num">.02</span>  Sign up</li>
                  <li><span class="span-num">.03</span>  Find the Course you Want</li>
              </ul>
               <q-btn push color="secondary" label="Push" >Sign Up</q-btn>
          </div>
      </div>
      <div class="style-right col-sm-6 col-md-6 q-ma-none q-pa-none text-center justify-center ">
          <q-img class="content-img"
            src="/statics/computer.png"
          />
          <div>
            <q-icon :name="matMenu" />
            <q-icon :name="fasFont" />
            <q-btn :icon="mdiAbTesting" />
          </div>
      </div>
      
    </div>
  </q-page>
</template>

<script>
export default {
}
</script>
<style lang="scss">
.content-img {
  width: 200px;
  height: 200px;
  border-radius: 200px;
}
.title{
  font-size: 14px;
  font-weight: 900;
}
.style-header{
  position: relative;
  // height: 20px;
}
.styleDiv{
  height: 100%;
  // border: 1px solid gray;
}
.styleToolbar{
  width: 100%;
  display: grid;
  grid-template-columns:  2fr 3fr 1fr;
  align-items: center;
}

.content-body{
  // width: 100%;
  margin: 6rem;
  text-align: start;
}
.list-style{
  padding: 0;
  text-align: start;
  align-items: center;
  list-style: none;
}
.style-right{
  background: #99d6e9;
  border-radius: 50px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.togle-list label{
  font-size: 12px;
  text-transform: lowercase;
}
.style-ul{
  display: flex;
  flex-direction: row;
  text-decoration: none;
  list-style: none;
  font-size: 13px;
}
.span-num{
  color: #99d6e9;;
  font-size: 10px;
  font-weight: 800;
  margin: .5rem;
}
</style>