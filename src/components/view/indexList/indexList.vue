<template>
	<div class="my-product">
		<div class="temp-cb el-c-master-light">
			<span>会议管理 > </span>
			<span class="el-c-primary">中科院力学研究所</span>
		</div>

		<div>
			<el-radio-group v-model="radio3">
				<el-radio-button label="上海"></el-radio-button>
				<el-radio-button label="北京"></el-radio-button>
				<el-radio-button label="广州"></el-radio-button>
				<el-radio-button label="深圳"></el-radio-button>
			</el-radio-group>
		</div>

		<div class="">

		</div>
	</div>
</template>

<script>
	export default {
		data: function () {
			return {
				aa: '',
				tabPosition: '1',
				currentPage: '1',
				params: {
					sex: '1',
					education: '1',
					degree: '1',
					status: '1'
				},
				options: [{
					value: '1',
					label: '男'
				}, {
					value: '2',
					label: '女'
				}],
				degree: [{
					value: '1',
					label: '大学'
				}, {
					value: '2',
					label: '高中'
				}],
				education: [{
					value: '1',
					label: '全部'
				}, {
					value: '2',
					label: '学士'
				}],
				status: [{
					value: '1',
					label: '全部'
				}, {
					value: '2',
					label: '待审核'
				}],
				tableData3: [{
					date: '人脸识别APP应用开发',
					name: '2016-05-03',
					address: '王小虎'
				},{
					date: '人脸识别APP应用开发',
					name: '2016-05-03',
					address: '王小虎'
				},{
					date: '人脸识别APP应用开发',
					name: '2016-05-03',
					address: '王小虎'
				},{
					date: '人脸识别APP应用开发',
					name: '2016-05-03',
					address: '王小虎'
				},{
					date: '人脸识别APP应用开发',
					name: '2016-05-03',
					address: '王小虎'
				},{
					date: '人脸识别APP应用开发',
					name: '2016-05-03',
					address: '王小虎'
				}],
				multipleSelection: []
			}
		},
		methods: {
			handleSizeChange() {

			},
			handleCurrentChange() {

			}
		},
		computed: function () {
			return {}
		},
		compontes: {},
		mounted: function () {

		},
		created: function () {

		}
	}
</script>
<style rel="stylesheet/sass" lang="sass">
	.my-product
		.el-table__body-wrapper
			.el-table__row
				td:nth-last-child(1)
					.cell
						visibility: hidden!important

		.my-product
			.el-table__body-wrapper
				.el-table__row:hover
					td:nth-last-child(1)
						.cell
							visibility: visible!important

			.el-table__header-wrapper th
				border-right: 1px solid #e1e1e1
				border-bottom: none!important

			.el-table__header-wrapper th:nth-last-child(2)
				border-right: none!important
			.pagination-com .el-pagination__total
				margin-top: -3px

			.pagination-com .el-pagination__sizes
				margin-top: -3px
			.com-select .el-form-item
				margin-bottom: 0 !important
				margin-right: 20px
</style>

<style scoped rel="stylesheet/sass" lang="sass">
	.temp-cb
		font-size: 12px
		position: absolute
		top: 73px
		left: 100px
	.my-product
		background: #e8ebf1
</style>
