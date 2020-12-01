
<script>
import Vue from 'vue';

export default 

Vue.component('RenderBind',
    {
        data: function() {
            return {
                ii: 'aaa@sina.cn'
            }
        },
        methods: {
            onClick(e) {
                console.log(e);
            }
        },
        render: function(h) {
            const inputAttrs = {
                type: 'email',
                placeholder: 'Enter your email'
            };
            return (
                <div>
                <input type="email" placeholder={this.ii}/>
                <input {...{attrs: inputAttrs}}/>
                <input vModel={this.ii}/>
                <button vOn:click={this.onClick}>click</button>
                </div>
            )
        }
    }
)    

</script>