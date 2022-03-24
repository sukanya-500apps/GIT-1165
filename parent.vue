<template>
    <div class=parent-component>
<childcomponent:message="message"/>
    </div>
</template>
<script>
import  childcomponent  from "@/components.child.vue"

export default {
       name:"parentcomponent" ,
       data(){
       return {
           message:"hi sukanya",
       };
    },
    components:{
    childcomponent,
},
    };
</script>
