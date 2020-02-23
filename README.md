# webcourse
前端开发
ElementUI
按需引入
	// import { Button,Row } from 'element-ui'
	
	// Vue.use(Button)
	// Vue.use(Row)

	然后，将 .babelrc 修改为：
	// {
	//   "presets": [
	//     ["env", {
	//       "modules": false,
	//       "targets": {
	//         "browsers": ["> 1%", "last 2 versions", "not ie <= 8"]
	//       }
	//     }],
	//     "stage-2"
	//   ],
	//   "plugins": ["transform-vue-jsx", "transform-runtime",[
	//     "component",
	//     {
	//       "libraryName": "element-ui",
	//       "styleLibraryName": "theme-chalk"
	//     }
	//   ]]
	// }
