
<template>
<div class="flex flex-wrap diygw-col-24 flex-direction-column">
					<div class="flex diygw-col-24">
						<div class="diygw-list">
							<div style="" class="diygw-item col-100 row solid-bottom">
								<div class="diygw-avatar">
									<img mode="aspectFit" class="diygw-avatar-img" src="./static/icon1_rm.png" />
								</div>
								<div class="content">
									<div class="title">เงื่อนไขกิจกรรม</div>
									<div class="text-sm remark">
										<p><span style="color: #fe1919">ค่าตอบแทน 10 บาท</span></p>
									</div>
								</div>
							</div>
						</div>
					</div>
					<div class="diygw-text-line3 diygw-col-24 text31-clz">
						<p>1.</p>
						<p>2.</p>
						<p>3. </p>
					</div>
					<div class="flex diygw-col-24 items-center flex-nowrap">
						<img src="./static/diygwjpg" class="image16-size diygw-image diygw-col-0 image16-clz" mode="widthFix" />
					</div>
					<div class="flex diygw-col-24 justify-between">
						<div class="diygw-tag diygw-capsule">
							<div class="diygw-tag bg-pink md radius">
								<span class="diygw-icon diy-icon-share"></span>
							</div>
							<div class="diygw-tag diygw-line-pink radius md">แชร์</div>
						</div>
						<div class="diygw-tag diygw-capsule">
							<div class="diygw-tag bg-purple md radius">
								<span class="diygw-icon diy-icon-comment"></span>
							</div>
							<div class="diygw-tag diygw-line-purple radius md">ถูกใจ</div>
						</div>
						<div class="diygw-tag diygw-capsule">
							<div class="diygw-tag bg-green md radius">
								<span class="diygw-icon diy-icon-appreciate"></span>
							</div>
							<div class="diygw-tag diygw-line-green radius md">คงเหลือ 120 สิทธ์</div>
						</div>
					</div>
					<div class="flex diygw-col-24">
						<div class="diygw-pzx" style="border-bottom: 5px solid #eee"></div>
					</div>
				</div>
				<div class="flex flex-wrap diygw-col-24">
					<div class="flex diygw-col-12 flex-direction-column justify-center items-center flex-nowrap flex3-clz">
						<img src="./static/wbt-3jpg" class="image1-size diygw-image diygw-col-24 image1-clz" mode="widthFix" />
						<div class="diygw-col-0 text-clz">DIY视频教程</div>
						<div class="diygw-col-0 text1-clz">免费领取</div>
					</div>
					<div class="flex diygw-col-12 flex-direction-column justify-center items-center flex-nowrap flex4-clz">
						<img src="./static/d3ad3a6bf322e6b7d8c6a7fa09e80f26.jpg" class="image3-size diygw-image diygw-col-24 image3-clz" mode="widthFix" />
						<div class="diygw-col-0 text2-clz">DIY视频教程</div>
						<div class="diygw-col-0 text3-clz">免费领取</div>
					</div>
				</div>
				<div class="diygw-title flex diygw-col-24">
					<div class="title font-normal">榜单</div>
				</div>
				<scroll-view @scrolltoupper="scrolltoupperFlex5" @scrolltolower="scrolltolowerFlex5" scroll-x scroll-with-animation class="flex scroll-view diygw-col-24 flex-nowrap flex5-clz">
					<div class="flex flex-nowrap">
						<div class="flex flex-wrap diygw-col-21 flex-direction-column flex7-clz">
							<div class="diygw-title flex gradual-orange diygw-col-24">
								<div class="title font-normal">热门课程Top50</div>
								<div class="more">
									<span class="diy-icon-right"></span>
								</div>
							</div>
							<div class="flex diygw-col-24">
								<div class="diygw-list">
									<div style="" class="diygw-item col-100 row arrow solid-bottom list1-item-clz">
										<div class="diygw-avatar list1-icon-clz">
											<img mode="aspectFit" class="diygw-avatar-img" src="./static/wbt-4jpg" />
										</div>
										<div class="content">
											<div class="title">设计新人【实战DIY可视化】</div>
											<div class="text-sm remark">教大家如何快速用DIY可视化做项目</div>
										</div>
									</div>
									<div style="" class="diygw-item col-100 row arrow solid-bottom list1-item-clz">
										<div class="diygw-avatar list1-icon-clz">
											<img mode="aspectFit" class="diygw-avatar-img" src="./static/wbt-3jpg" />
										</div>
										<div class="content">
											<div class="title">设计新人【实战DIY可视化】</div>
											<div class="text-sm remark">教大家如何快速用DIY可视化做项目</div>
										</div>
									</div>
									<div style="" class="diygw-item col-100 row arrow solid-bottom list1-item-clz">
										<div class="diygw-avatar list1-icon-clz">
											<img mode="aspectFit" class="diygw-avatar-img" src="./static/wbt-4jpg" />
										</div>
										<div class="content">
											<div class="title">设计新人【实战DIY可视化】</div>
											<div class="text-sm remark">教大家如何快速用DIY可视化做项目</div>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="flex flex-wrap diygw-col-21 flex-direction-column flex11-clz">
							<div class="diygw-title flex gradual-red diygw-col-24">
								<div class="title font-normal">热门课程Top50</div>
								<div class="more">
									<span class="diy-icon-right"></span>
								</div>
							</div>
							<div class="flex diygw-col-24">
								<div class="diygw-list">
									<div style="" class="diygw-item col-100 row arrow solid-bottom list6-item-clz">
										<div class="diygw-avatar list6-icon-clz">
											<img mode="aspectFit" class="diygw-avatar-img" src="./static/wbt-4jpg" />
										</div>
										<div class="content">
											<div class="title">设计新人【实战DIY可视化】</div>
											<div class="text-sm remark">教大家如何快速用DIY可视化做项目</div>
										</div>
									</div>
									<div style="" class="diygw-item col-100 row arrow solid-bottom list6-item-clz">
										<div class="diygw-avatar list6-icon-clz">
											<img mode="aspectFit" class="diygw-avatar-img" src="./static/wbt-3jpg" />
										</div>
										<div class="content">
											<div class="title">设计新人【实战DIY可视化】</div>
											<div class="text-sm remark">教大家如何快速用DIY可视化做项目</div>
										</div>
									</div>
									<div style="" class="diygw-item col-100 row arrow solid-bottom list6-item-clz">
										<div class="diygw-avatar list6-icon-clz">
											<img mode="aspectFit" class="diygw-avatar-img" src="./static/wbt-4jpg" />
										</div>
										<div class="content">
											<div class="title">设计新人【实战DIY可视化】</div>
											<div class="text-sm remark">教大家如何快速用DIY可视化做项目</div>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="flex flex-wrap diygw-col-3 flex-direction-column"></div>
					</div>
				</scroll-view>
				<div class="flex diygw-col-24">
					<div class="diygw-pzx" style="border-bottom: 5px solid #eee"></div>
				</div>
				<div class="flex flex-wrap diygw-col-24 flex-direction-column">
					<div class="flex diygw-col-24">
						<div class="diygw-list">
							<div style="" class="diygw-item col-100 row solid-bottom">
								<div class="diygw-avatar">
									<img mode="aspectFit" class="diygw-avatar-img" src="./static/icon1_rm.png" />
								</div>
								<div class="content">
									<div class="title">DIY可视化</div>
									<div class="text-sm remark">3天前 DIY可视化公司</div>
								</div>
							</div>
						</div>
					</div>
					<div class="flex diygw-col-24">
						<div class="diygw-list">
							<div style="" class="diygw-item col-100 flex-direction-row-reverse solid-bottom list4-item-clz">
								<div class="diygw-avatar list4-icon-clz">
									<img mode="aspectFit" class="diygw-avatar-img" src="./static/miniprogramcode_177png" />
								</div>
								<div class="content">
									<div class="title">DIY可视化开源推荐</div>
									<div class="text-sm remark">DIY官网可视化工具做好的可视化拖拽开发工具，无须编程、零代码基础、所见即所得设计工具，轻松制作微信小程序、支付宝小程序、Vue3、H5、WebApp、UNIAPP、单页动画</div>
								</div>
							</div>
						</div>
					</div>
					<div class="flex diygw-col-24 justify-between">
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-share"></span>
							<span> 1000 </span>
						</div>
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-comment"></span>
							<span> 1000 </span>
						</div>
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-appreciate"></span>
							<span> 2020-2-12 </span>
						</div>
					</div>
					<div class="flex diygw-col-24">
						<div class="diygw-pzx" style="border-bottom: 5px solid #eee"></div>
					</div>
				</div>
				<div class="flex flex-wrap diygw-col-24 flex-direction-column">
					<div class="flex diygw-col-24">
						<div class="diygw-list">
							<div style="" class="diygw-item col-100 row solid-bottom">
								<div class="diygw-avatar">
									<img mode="aspectFit" class="diygw-avatar-img" src="./static/icon1_rm.png" />
								</div>
								<div class="content">
									<div class="title">DIY可视化</div>
									<div class="text-sm remark">3天前 DIY可视化公司</div>
								</div>
							</div>
						</div>
					</div>
					<div class="diygw-col-24 text5-clz">DIY官网可视化工具做好的可视化拖拽开发工具，无须编程、零代码基础、所见即所得设计工具，轻松制作微信小程序、支付宝小程序、Vue3、H5、WebApp、UNIAPP、单页动画</div>
					<div class="flex diygw-col-24 items-center flex-nowrap">
						<img src="./static/diygwjpg" class="image-size diygw-image diygw-col-0 image-clz" mode="widthFix" />
					</div>
					<div class="flex diygw-col-24 justify-between">
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-share"></span>
							<span> 1000 </span>
						</div>
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-comment"></span>
							<span> 1000 </span>
						</div>
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-appreciate"></span>
							<span> 2020-2-12 </span>
						</div>
					</div>
					<div class="flex diygw-col-24">
						<div class="diygw-pzx" style="border-bottom: 5px solid #eee"></div>
					</div>
				</div>
				<div class="flex flex-wrap diygw-col-24 flex-direction-column">
					<div class="flex diygw-col-24">
						<div class="diygw-list">
							<div style="" class="diygw-item col-100 row solid-bottom">
								<div class="diygw-avatar">
									<img mode="aspectFit" class="diygw-avatar-img" src="./static/icon1_rm.png" />
								</div>
								<div class="content">
									<div class="title">DIY可视化</div>
									<div class="text-sm remark">3天前 DIY可视化公司</div>
								</div>
							</div>
						</div>
					</div>
					<div class="diygw-col-24 text6-clz">DIY官网可视化工具做好的可视化拖拽开发工具，无须编程、零代码基础、所见即所得设计工具，轻松制作微信小程序、支付宝小程序、Vue3、H5、WebApp、UNIAPP、单页动画</div>
					<div class="flex diygw-col-24 items-center flex-nowrap">
						<img src="./static/pic1.jpg" class="image4-size diygw-image diygw-col-0 image4-clz" mode="widthFix" />
						<img src="./static/diygwjpg" class="image6-size diygw-image diygw-col-0 image6-clz" mode="widthFix" />
					</div>
					<div class="flex diygw-col-24 justify-between">
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-share"></span>
							<span> 1000 </span>
						</div>
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-comment"></span>
							<span> 1000 </span>
						</div>
						<div class="diygw-tag md radius">
							<span class="diygw-icon diy-icon-appreciate"></span>
							<span> 2020-2-12 </span>
						</div>
					</div>
					<div class="flex diygw-col-24">
						<div class="diygw-pzx" style="border-bottom: 5px solid #eee"></div>
					</div>
				</div>


    </template>