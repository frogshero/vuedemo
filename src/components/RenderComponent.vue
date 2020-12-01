
<script>
import Vue from 'vue'

export default 
({props}) => <div>
                 <span>{props.tt}</span>
             </div>

// Vue.component('RenderComponent',
//     {
//         funtional: true,
//         props: {
//             tt: String
//         },
//         render: function (h) {
//             return (
//             <div>
//                 <span>{this.tt}</span>
//             </div>
//             )
//         }
//     }       
// )
</script>
