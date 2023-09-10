

<template>
<div class="flex diygw-col-24 justify-between items-center flex-nowrap flex-clz">
					<div class="diygw-col-19">
						<div class="diygw-search">
							<div class="flex1 align-center flex padding-xs solid radius">
								<span style="color: #555 !important" class="diy-icon-search"></span>
								<van-field class="flex1" name="search1" type="" v-model="search1" placeholder="พิมพ์คำที่ต้องการค้นหา"></van-field>
							</div>
						</div>
					</div>
					<div class="flex diygw-col-0">
						<div class="diygw-avatar xs radius bg-none">
							<img mode="aspectFit" class="diygw-avatar-img radius" src="./static/icon15_yj.png" />
							<div class="diygw-tag badge avatar-badge-0 red">1</div>
						</div>
					</div>
					<div class="flex diygw-col-0">
						<div class="diygw-tag margin-xs radius">
							<img class="diygw-tag-img" src="./static/icon8_qd.png" />
							<span> เช็คอิน </span>
						</div>
					</div>
				</div>

</template>