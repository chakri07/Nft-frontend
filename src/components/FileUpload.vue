<template>
      <input ref="file" v-on:change="handleFileUpload()"  type="file">
</template>
<script>

import { ref} from "vue"

export default{
    name:'FileUpload',

    setup() {
        const file = ref(null)

        const handleFileUpload = async() => {
           // debugger;
            console.log("selected file",file.value.files)
            //do a post Request
        }

        return {
          handleFileUpload,
          file
       }
    }
}

</script>