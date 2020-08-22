<template>
    <div class="d-flex flex-column flex-md-row  align-center justify-md-space-between second__nav"> 
        <div class="nav__left_side d-flex align-center flex-wrap  justify-center">
                <v-btn class="mx-1 my-2 px-2 font-weight-light  text-capitalize" outlined color="grey lighten-5" @click="filterShow"> 
                <v-icon v-if="filter">
                keyboard_arrow_up
                </v-icon>
                <v-icon v-if="!filter">
                keyboard_arrow_down
                </v-icon>
                 Filter is active</v-btn>
                <v-btn class="mx-1 my-2 px-2 font-weight-light  text-capitalize" outlined color="grey lighten-5">  
                 From: 13. Aug 2020</v-btn>
                <v-btn class="mx-1 my-2 px-2 font-weight-light  text-capitalize" outlined color="grey lighten-5">  
                 To: 28. Aug 2020</v-btn>
                 <p class="ma-0 font-weight-light  text-capitalize d-block d-md-flex" style="color: white">Item Count: 2</p>
        </div>
        <div class="nav__right_side d-flex align-center ml-md-auto flex-wrap justify-center"> 
                <v-btn class="mx-1 my-2 px-2 font-weight-light  text-capitalize" outlined color="grey lighten-5">
                   <v-icon>
                    mail_outline
                    </v-icon>  
                 Send via email</v-btn> 
                <v-btn class="mx-1 my-2 px-2 font-weight-light  text-capitalize" outlined color="grey lighten-5">
                   <v-icon>
                    print
                    </v-icon>  
                 Print</v-btn> 
                <v-btn class="mx-1 my-2 px-2 font-weight-light  text-capitalize" outlined color="grey lighten-5">
                   <v-icon>
                    picture_as_pdf
                    </v-icon>  
                 PDF</v-btn> 
                <v-btn class="mx-1 my-2 px-2 font-weight-light  text-capitalize" outlined color="grey lighten-5">
                   <v-icon>
                    request_quote
                    </v-icon>  
                 CSV</v-btn> 
        </div>
          <transition name="slide">
       <div class="filter__dropdown" v-if="filter">
          <div class="d-flex filter__sub">
              <div class="left__side">
                  <ul class="tag_list">
                    <li>Time Intervals</li>
                    <li>External</li>
                    <li>Internal</li>
                    <li>Status</li>
                    <li>Reporter</li>
                    <li>Description</li>
                    <li>id</li>
                  </ul>
              </div>
              <div class="right__side">
                <ul class="tag_list">
                    <li>Time Intervals</li>
                    <li>External</li>
                    <li>Internal</li>
                    <li>Status</li>
                    <li>Reporter</li>
                    <li>Description</li>
                    <li>id</li>
                    <li>Time Intervals</li>
                    <li>External</li>
                    <li>Internal</li>
                    <li>Status</li>
                    <li>Reporter</li>
                    <li>Description</li>
                    <li>id</li>
                    <li>Time Intervals</li>
                    <li>External</li>
                    <li>Internal</li>
                    <li>Status</li>
                    <li>Reporter</li>
                    <li>Description</li>
                    <li>id</li>
                  </ul>

                  <div class="input__group_main">
                      <input type="text" class="input__filter" placeholder="Reporter name">
                      <input type="text" class="input__filter" placeholder="Description">
                      <input type="text" class="input__filter" placeholder="Report ID">
                  </div>
              </div>

          </div>
          <div class="filter__footer d-flex justify-center py-1" @click="filterShow">
                <v-icon>
                keyboard_arrow_up
                </v-icon>  Save Filter
          </div>
        </div>
   </transition>
     
    </div>
</template>
<script> 
export default { 
  data () {
    return {
      filter: false
    }
  },
  methods: {
    filterShow(){
      this.filter = !this.filter
    }
  }
}
</script>
<style lang="scss">
    .second__nav{
      background: #2392db;
      position: relative;
    }
    .filter__sub{
   padding: 10px;
    }
    .filter__dropdown{
       position: absolute;
        top: 52px;
        width: 100%;
        background:#eee;
        z-index: 99;
   
    }
    .left__side{ 
      padding-right: 20px;
      border-right: 1px solid #ddd;
          .tag_list{
              list-style: none;
              display: flex;
              flex-direction: column;
              align-items: flex-end;
                li{
                  padding: 4px 9px;
                  background: #d8d8d8;
                  border-radius: 50px;
                  margin: 2px;
                  cursor: pointer;
                  &:hover{
                    background: #aaaaaa;
                    color: white;
                  }
                }
           } 
    }
      .right__side{
        width: 700px;
           .tag_list{
                list-style: none;
                display: flex; 
                flex-wrap: wrap;
                  li{
                    padding: 4px 9px;
                    background: #d8d8d8;
                    border-radius: 50px;
                    margin: 2px;
                    cursor: pointer;
                    &:hover{
                      background: #aaaaaa;
                      color: white;
                    }
                  }
            } 
      }
      .filter__footer{
        background: #c0c0c0 !important; 
        cursor: pointer;
      }
      .input__group_main{
            display: flex;
            flex-direction: column;
            margin-left: 20px;
            margin-top: 15px;
        .input__filter {
            outline: 0;
            border: 1px solid #fff;
            margin: 5px;
            padding: 5px;
            border-radius: 10px;
            width: 200px;
            background: #fff;
        }
      }

      .slide-enter-active {
   -moz-transition-duration: 0.3s;
   -webkit-transition-duration: 0.3s;
   -o-transition-duration: 0.3s;
   transition-duration: 0.3s;
   -moz-transition-timing-function: ease-in;
   -webkit-transition-timing-function: ease-in;
   -o-transition-timing-function: ease-in;
   transition-timing-function: ease-in;
}

.slide-leave-active {
   -moz-transition-duration: 0.3s;
   -webkit-transition-duration: 0.3s;
   -o-transition-duration: 0.3s;
   transition-duration: 0.3s;
   -moz-transition-timing-function: cubic-bezier(0, 1, 0.5, 1);
   -webkit-transition-timing-function: cubic-bezier(0, 1, 0.5, 1);
   -o-transition-timing-function: cubic-bezier(0, 1, 0.5, 1);
   transition-timing-function: cubic-bezier(0, 1, 0.5, 1);
}

.slide-enter-to, .slide-leave {
   max-height: 100px;
   overflow: hidden;
}

.slide-enter, .slide-leave-to {
   overflow: hidden;
   max-height: 0;
}
</style>
 
