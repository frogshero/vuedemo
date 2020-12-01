
<script>
import Vue from 'vue'

export default 
Vue.component('RenderComponent',
    {
        render: function (h) {
            return (
            <H1>
                <span>Hello</span> world!
            </H1>
            )
        }
    }       
)
</script>
