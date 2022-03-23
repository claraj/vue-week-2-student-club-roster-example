1. Include the Vue script

`<script src="https://unpkg.com/vue@next"></script>`

2. Create a div to enclose all the HTML that Vue should manage 

3. Set up your Vue app 

```

let app = Vue.createApp({
    data() {
        return {
            ...
        }
    },
    methods: {
       ...
    }
})

app.mount('#app')  // match your div's id

```

4. Define Vue data
5. Define events - add, remove, select 
6. Optional computed property for student count

