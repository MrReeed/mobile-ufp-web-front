<template>
	<view class="home">
		<view class="home_content">
			<!-- 所有内容的容器 -->
			<view class="username_bar">
				<text>用户名称</text>
				<view>
					<text>NFC</text>
					<u-icon name="email" size="40"></u-icon>
				</view>
			</view>
			<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000">
				<swiper-item>
					<image src="https://i.postimg.cc/3rcQ1gtw/lunbotu.jpg" mode="aspectFit"></image>
				</swiper-item>
				<swiper-item>
					<image src="https://i.postimg.cc/3rcQ1gtw/lunbotu.jpg" mode="aspectFit"></image>
				</swiper-item>
			</swiper>
			<view class="work_function">
				<view class="work_function_item">
					<svg t="1615794329995" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="1821"
					 width="55" height="60">
						<path d="M641.1 452.3c-89.5-99.5-89.5-218.8-89.5-387.9C273 173.8 342.7 472.2 332.7 571.6c-69.6-59.6-89.5-198.9-89.5-198.9-79.5 39.8-119.3 139.3-119.3 218.8 4.3 205.3 172.6 369.2 377.9 368 204 4.7 373.2-156.9 377.8-360.8 0.1-2.4 0.1-4.8 0.1-7.2 0-119.4-89.5-179-89.5-338.2-90.9 22.1-153.4 105.5-149.1 199z"
						 fill="#FF6B6A" p-id="1822"></path>
						<path d="M491.8 551.7c129.3 49.7 99.5 189 99.5 228.7 20.7-26 34.3-56.8 39.8-89.5 31.5 23.3 50 60.3 49.7 99.5 0 93.4-75.7 169.1-169.1 169.1s-169-75.7-169-169c9.9-89.6 149.1-159.2 149.1-238.8z"
						 fill="#FFA9B1" p-id="1823"></path>
					</svg>
					<text>火灾报警</text>
				</view>
				<view class="work_function_item">
					<svg t="1615795021408" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="2307"
					 width="60" height="57">
						<path d="M711.8 835.7H312.2c-17.8 0.1-32.4-14.2-32.5-32V490.5c-0.1-60.9 24.4-119.2 67.9-161.8 91.3-89.3 237.2-89.3 328.5 0 43.5 42.6 68 100.9 67.9 161.8v313.1c0.1 17.6-14.2 32-31.8 32.1h-0.4z m199.8-313.2h-88.8c-17.7 0-32.1-14.3-32.1-32s14.3-32.1 32-32.1H911.6c17.7 0 32.1 14.3 32.1 32s-14.3 32-32.1 32.1z m-710.4 0h-88.8c-17.7 0-32.1-14.3-32.1-32s14.3-32.1 32-32.1H201.2c17.7 0 32.1 14.3 32.1 32s-14.3 32.1-32 32.1h-0.1zM512 216.3c-17.8 0.1-32.4-14.2-32.5-32V96.7c0-18 14.6-32.5 32.5-32.5 18 0 32.5 14.6 32.5 32.5v87.5c-0.1 17.8-14.7 32.2-32.5 32.1z m219.8 89.6c-8.6 0-16.9-3.3-23-9.4-12.5-12.3-12.7-32.4-0.4-44.9 0.1-0.2 0.3-0.3 0.4-0.4l68.8-67.8c12.8-12.5 33.2-12.5 46 0 12.5 12.3 12.7 32.4 0.4 44.9-0.1 0.2-0.3 0.3-0.4 0.4l-68.8 67.8c-6.1 6-14.4 9.4-23 9.4z m-439.5 0c-8.6 0-16.9-3.3-23-9.4l-68.8-67.8c-12.5-12.3-12.7-32.4-0.4-44.9 0.1-0.2 0.3-0.3 0.4-0.4 12.8-12.5 33.2-12.5 46 0l68.8 67.8c12.5 12.3 12.7 32.4 0.4 44.9-0.1 0.2-0.3 0.3-0.4 0.4-6.1 6-14.4 9.4-23 9.4z m563.9 653.9H167.9c-17.7 0-32.1-14.3-32.1-32s14.3-32.1 32-32.1H856c17.7 0 32.1 14.3 32.1 32 0.1 17.7-14.3 32.1-31.9 32.1z"
						 fill="#FB8685" opacity=".89" p-id="2308"></path>
						<path d="M664.7 782.5H365c-14-0.5-24.9-12.2-24.4-26.1V500.7c-0.4-48.9 17.8-96.1 51-132.1 61.5-68 166.6-73.3 234.6-11.8 4.1 3.7 8 7.6 11.8 11.8 33.1 36 51.4 83.2 51 132.1v255.6c0.6 13.8-10.1 25.5-23.9 26.1-0.2 0.1-0.3 0.1-0.4 0.1z"
						 fill="#F95456" opacity=".89" p-id="2309"></path>
						<path d="M487.9 504.7H545c18.3 0 33.1 14.8 33.1 33.1v244.7H454.7V537.8c0-18.3 14.9-33.1 33.2-33.1z" fill="#FFB1AE"
						 opacity=".58" p-id="2310"></path>
					</svg> <text>电气隐患</text>
				</view>
				<view class="work_function_item">
					<svg t="1615795080003" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="2746"
					 width="60" height="60">
						<path d="M954.9 860.33l-413.4-730c-9.3-16.3-30-22.1-46.3-12.8-5.3 3-9.8 7.5-12.8 12.8L69.1 860.23c-9.3 16.3-3.5 37.1 12.8 46.3 5.1 2.9 11 4.4 16.9 4.4h826.7c12.1-0.1 23.2-6.5 29.3-16.9 6-10.4 6.1-23.2 0.1-33.7z"
						 fill="#fb7170" p-id="2747" data-spm-anchor-id="a313x.7781069.0.i19" class="selected"></path>
						<path d="M626 617.33l-70.2 172.3c-5.5 13.3-18.5 22.1-32.9 22.1-4.6 0-9.2-0.9-13.4-2.7-18.2-7.4-26.9-28.1-19.6-46.3l50.2-123.3h-88.8c-19.7-0.1-35.6-16.1-35.5-35.7 0-5.4 1.3-10.8 3.7-15.7l85-170c7.2-18.3 27.9-27.3 46.2-20 18.3 7.2 27.3 27.9 20 46.2-0.8 1.9-1.7 3.8-2.8 5.6l-59.4 118.5h84.2c19.6-0.1 35.5 15.7 35.6 35.3 0 4.7-0.9 9.4-2.7 13.7h0.4z"
						 fill="#FFF1DF" p-id="2748"></path>
					</svg> <text>消防隐患</text>
				</view>
				<view class="work_function_item">
					<svg t="1615795273343" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="5172"
					 width="55" height="60">
						<path d="M799.32 959.508h-574.2c-81.9 0.1-148.3-66.3-148.4-148.1v-537.1c0.3-81.8 66.6-148.1 148.4-148.4v63.8c-46.6 0 620.3 0 573.7-63.8 81.9-0.1 148.3 66.3 148.4 148.1V810.908c0.4 81.6-65.5 148.1-147.1 148.5-0.3 0.1-0.5 0.1-0.8 0.1z"
						 fill="#fb7170" p-id="5173" data-spm-anchor-id="a313x.7781069.0.i61" class="selected"></path>
						<path d="M735.32 251.608h-446.6c-51.7 0-93.7-41.9-93.7-93.7s41.9-93.7 93.7-93.7h446.6c51.7 0 93.7 41.9 93.7 93.7s-42 93.7-93.7 93.7z"
						 fill="#fb7170" p-id="5174" data-spm-anchor-id="a313x.7781069.0.i62" class="selected"></path>
						<path d="M734.02 219.908h-444.6c-21.7-4.8-35.3-26.3-30.5-48 3.4-15.2 15.3-27.1 30.5-30.5h444.6c19.4 2.4 33.5 19.7 31.9 39.3 1.2 19.3-12.7 36.3-31.9 39.2z"
						 fill="#ffa9b1" p-id="5175" data-spm-anchor-id="a313x.7781069.0.i60" class=""></path>
						<path d="M385.632 748.268c-13.4-13.3-13.4-34.9-0.1-48.2 0-0.1 0.1-0.1 0.1-0.1l337.2-337.2c13.7-13 35.3-12.5 48.4 1.2 12.5 13.2 12.5 33.9 0 47.1l-337.5 337.2c-13.1 13.3-34.4 13.4-47.7 0.4l-0.4-0.4z"
						 fill="#FCFCFC" p-id="5176"></path>
						<path d="M434.132 748.268c-13.3 13.4-34.9 13.4-48.2 0.1l-0.1-0.1-131.8-131.7c-13.7-13-14.2-34.7-1.2-48.4 13-13.7 34.7-14.2 48.4-1.2l1.2 1.2 131.7 131.7c0.6 3.8-108.2 26.1 0 48.4z"
						 fill="#FCFCFC" p-id="5177"></path>
					</svg> <text>消控室值班</text>
				</view>
			</view>
			<view class="medium_image">
				<image src="https://i.postimg.cc/4yqC3gYc/xinshouzhiyin.jpg" mode="aspectFill"></image>
			</view>
			<view class="ShiShiJianCe">
				<view class="shishijiance_bar">
					<text>实时监测</text>
					<view>
						<text>全部设备</text>
						<u-icon name="arrow-right"></u-icon>
					</view>
				</view>
				<view class="shishijiance_content">
					<view class="shishijiance_content_item">
						<text>5</text>
						<text>火警</text>
					</view>
					<view class="shishijiance_content_item">
						<text>1</text>
						<text>预警</text>
					</view>
					<view class="shishijiance_content_item">
						<text>6</text>
						<text>故障</text>
					</view>
					<view class="shishijiance_content_item">
						<text>290</text>
						<text>异常</text>
					</view>
				</view>
			</view>
			<view class="WeiBaoXunCha">
				<view class="weibaoxuncha_bar">
					<text>维保巡查</text>
				</view>
				<view class="weibaoxuncha_content">
					<view class="weibaoxuncha_content_item">
						<svg t="1615857157085" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="8855"
						 data-spm-anchor-id="a313x.7781069.0.i137" width="60" height="60">
							<path d="M855.788 178.762c-108.7-3.3-213.9-38.5-302.7-101.2-25-18-58.8-17.9-83.8 0.2-88.1 62.7-192.9 97.9-301.1 101-26.1 0.7-46.9 22-47.1 48.1v333.8c0 46.6 27.9 129.7 90.1 210.6 72.1 95 175.4 161.4 291.7 187.7 3 0.7 6 1 9 0.9h0.9c2.7 0 5.4-0.3 8.1-0.9 116.3-26.2 219.7-92.7 291.8-187.7 62.2-81 90.1-164.1 90.1-210.6v-333.8c0-26.1-20.9-47.4-47-48.1z"
							 fill="#81b7fe" opacity=".49" p-id="8856" data-spm-anchor-id="a313x.7781069.0.i136" class=""></path>
							<path d="M795.239 237.442c-89.5-2.7-176.2-31.7-249.4-83.3-20.6-14.8-48.5-14.8-69 0.1-72.6 51.7-159 80.6-248.1 83.2-21.5 0.6-38.6 18.1-38.8 39.6v275.1c0 38.3 23 106.9 74.2 173.5 59.4 78.3 144.5 133 240.3 154.7 2.4 0.6 4.9 0.8 7.4 0.7h0.7c2.2 0 4.5-0.3 6.7-0.7 95.9-21.6 181-76.4 240.4-154.7 51.3-66.7 74.2-135.2 74.2-173.5v-275.1c0-21.5-17.2-39.1-38.6-39.6z"
							 fill="#006fff" opacity=".49" p-id="8857" data-spm-anchor-id="a313x.7781069.0.i138" class="selected"></path>
							<path d="M447.439 712.342c0 33.1 26.9 60 60 60s60-26.9 60-60-26.9-60-60-60c-33.1-0.1-59.9 26.7-60 59.8v0.2zM460.939 606.342h92.7v-337.2h-92.7v337.2z"
							 fill="#FFEFD9" opacity=".49" p-id="8858"></path>
						</svg>
						<text>应急维保</text>
					</view>
					<view class="weibaoxuncha_content_item">
						<svg t="1615856885492" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="6874"
						 width="60" height="60">
							<path d="M906.807 301.421c-35.1-59.2-120.6-80-229.5-64.1-39.7-105.6-102.4-173.9-175.9-173.9-72.9 0-135.4 67.4-175.1 171.8-98-10.4-175.9 10.6-209 66.6-34.8 59-10.6 140.6 54.8 222.5-65.4 81.9-89.7 163.6-54.8 222.5 34.1 57.9 116.1 78.4 218.6 65.5 39.8 90.9 98.2 148.3 165.5 148.3 68 0 126.8-58.4 166.6-150.8 113.3 18.3 202.6-2 238.4-63.1 34.7-58.2 11.7-139.6-54.9-222.5 65.6-81.9 90.1-163.5 55.3-222.8z"
							 fill="#4e9bff" p-id="6875" data-spm-anchor-id="a313x.7781069.0.i103" class=""></path>
							<path d="M691.307 357.821c-56.4-1.7-111.1-20-157.2-52.6-13-9.4-30.5-9.4-43.5 0-45.8 32.6-100.2 50.8-156.4 52.5-13.6 0.4-24.4 11.4-24.4 25v173.4c4.5 40.3 20.8 78.4 46.8 109.4 37.5 49.3 91.1 83.9 151.5 97.5 1.5 0.3 3.1 0.5 4.7 0.5h0.5c1.4 0 2.8-0.2 4.2-0.5 60.4-13.6 114.1-48.2 151.6-97.5 26-31.1 42.3-69.1 46.8-109.4v-173.4c-0.1-13.5-11-24.6-24.6-24.9z"
							 fill="#9fc8fe" p-id="6876" data-spm-anchor-id="a313x.7781069.0.i105" class="selected"></path>
							<path d="M593.507 529.221l-97.6 114.6c-2.4 3.1-6.8 3.8-10 1.4-2.2-1.7-3.3-4.5-2.7-7.3l23.8-81.2h-49.2c-6.9-0.7-11.9-6.8-11.3-13.6 0.1-1.2 0.4-2.4 0.8-3.5l38.7-102.8c3.7-8.3 11.8-13.8 20.8-14.2h62.1c7.2 1 12.2 7.5 11.2 14.7-0.2 1.6-0.7 3.2-1.6 4.7l-42.5 70h48.4c5.7-0.6 10.8 3.6 11.4 9.4 0.3 2.8-0.5 5.6-2.3 7.8z"
							 fill="#FFFFFF" p-id="6877"></path>
						</svg>
						<text>例行维保</text>
					</view>
					<view class="weibaoxuncha_content_item">
						<svg t="1615856919094" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="7407"
						 width="60" height="60">
							<path d="M470.698 957.647c-9.3 0-18.5-1.8-27.1-5.2-28.2-11.1-46.7-38.4-46.8-68.7v-43.9c0-3.7-2.2-6.9-5.6-8.4l-0.5-0.2-0.7-0.3c-4.5-1.7-9.2-3.5-13.6-5.5l-6-2.6c-3.5-1.6-7.7-0.9-10.4 1.8l-31.1 31c-13.8 13.8-32.6 21.6-52.2 21.5-19.6 0.1-38.4-7.6-52.2-21.5l-58.6-58.6c-28.7-28.8-28.7-75.5 0-104.3l31.1-31c2.7-2.8 3.5-7 1.8-10.5-3-6.6-5.8-13.4-8.3-20.2 0-0.3-0.2-0.5-0.4-0.8-1.5-3.2-4.7-5.3-8.3-5.2h-43.9c-40.8 0-73.9-33.1-73.9-73.9v-83.2c0-40.8 33.1-73.9 73.9-73.9h43.9c3.9 0 7.3-2.5 8.6-6.1l1.4-3.5c2.2-5.6 4.5-11.2 6.9-16.7 1.7-3.5 1-7.7-1.8-10.4l-31.1-31c-13.8-13.8-21.5-32.6-21.5-52.2-0.1-19.6 7.7-38.4 21.5-52.2l58.8-58.8c28.8-28.7 75.4-28.7 104.2 0l31.1 31.1 0.3 0.3c2.8 2.5 6.8 3 10.1 1.4 6.6-3 13.4-5.8 20.2-8.3 1.3-0.5 2.5-1.3 3.5-2.3 1.7-1.7 2.6-4 2.5-6.4v-43.8c0-39.3 30.8-71.6 70-73.7h87c40.8 0 73.9 33.1 73.9 73.9v43.9c0 3.9 2.5 7.3 6.1 8.7 6.8 2.6 13.6 5.3 20.2 8.3 1.7 0.8 3.5 1.1 5.4 0.8 1.9-0.3 3.7-1.2 5.1-2.6l31.1-31c28.8-28.7 75.4-28.7 104.2 0l58.8 58.8c28.7 28.8 28.7 75.5 0 104.3l-31.1 31c-2.7 2.8-3.5 7-1.8 10.5 3 6.6 5.8 13.4 8.3 20.2 1.3 3.6 4.7 6.1 8.6 6.1h43.9c40.8 0 73.9 33.1 73.9 73.9v83.1c0 20.8-8.8 40.7-24.3 54.6a73.319 73.319 0 0 1-49.6 19.3h-43.9c-2.3 0-4.6 0.9-6.2 2.5-1 1-1.8 2.2-2.3 3.5l-0.6 1.4c-1.6 4.3-3.2 8.6-5.1 12.8-0.9 2-1.7 4-2.6 6a9.5 9.5 0 0 0 1.8 10.5l31.1 31c28.7 28.8 28.7 75.5 0 104.3l-58.8 58.8c-13.8 13.8-32.6 21.6-52.2 21.5-19.6 0.1-38.4-7.6-52.2-21.5l-31.1-31c-2.8-2.7-6.9-3.4-10.4-1.8-6.6 3-13.4 5.8-20.2 8.3l-0.7 0.3c-3.2 1.5-5.2 4.7-5.2 8.2v43.9c0 40.8-33.1 73.9-73.9 73.9l-83-0.2z"
							 fill="#4e9bff" p-id="7408" data-spm-anchor-id="a313x.7781069.0.i113" class=""></path>
							<path d="M590.298 412.947c-27.5-27.6-66-41.2-104.7-37.2-5.8 0.6-10 5.7-9.4 11.4 0.2 2.4 1.3 4.6 3 6.4l42.3 42.3c21 21.1 21 55.3 0 76.4l-15.3 15.3c-21.1 21-55.3 21-76.4 0l-42.3-42.3c-4.1-4.1-10.7-4-14.8 0.1-1.7 1.7-2.8 4-3 6.4-7.3 71.1 44.4 134.7 115.5 142 23.7 2.4 47.7-1.7 69.2-12l280.3 280.3c17.9 15.8 45.2 14.2 61-3.7 14.5-16.4 14.5-40.9 0-57.3l-280.2-280.6c23.7-49.6 13.6-108.7-25.2-147.5z"
							 fill="#9fc8fe" p-id="7409" data-spm-anchor-id="a313x.7781069.0.i114" class=""></path>
						</svg>
						<text>巡检巡查</text>
					</view>
					<view class="weibaoxuncha_content_item">
						<svg t="1615876930362" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4453"
						 width="55" height="55">
							<path d="M68.266667 68.266667v153.6H0V0h221.866667v68.266667zM955.733333 68.266667v153.6h68.266667V0H802.133333v68.266667z"
							 fill="#333333" p-id="4454"></path>
							<path d="M68.266667 955.733333v-153.6H0v221.866667h221.866667v-68.266667zM955.733333 955.733333v-153.6h68.266667v221.866667H802.133333v-68.266667z"
							 fill="#333333" p-id="4455"></path>
							<path d="M273.066667 307.2h477.866666a34.133333 34.133333 0 0 1 34.133334 34.133333v358.4a34.133333 34.133333 0 0 1-34.133334 34.133334H273.066667a34.133333 34.133333 0 0 1-34.133334-34.133334V341.333333a34.133333 34.133333 0 0 1 34.133334-34.133333z m74.3424 158.088533h23.1424c13.653333 0 20.48 5.461333 20.48 16.3328-0.426667 12.1856-7.253333 18.500267-20.48 18.944h-23.1424v-35.2768zM422.126933 580.266667l-36.369066-59.4432c18.944-4.795733 28.433067-17.646933 28.433066-38.5536 0-25.685333-14.984533-38.536533-44.970666-38.536534H324.266667v136.533334h23.1424v-58.146134h15.189333L395.690667 580.266667h26.453333z m97.160534-114.978134V443.733333h-76.032v136.533334h23.1424v-60.757334h44.288v-21.5552h-44.288v-32.6656h52.8896zM543.061333 443.733333v136.533334h23.1424v-136.533334H543.061333z m94.5152 21.5552c26.453333 0 39.662933 15.4624 39.662934 46.3872 0.443733 32.221867-12.561067 47.906133-38.997334 47.035734h-19.831466v-93.422934h19.165866zM636.928 580.266667c42.325333 0.426667 63.249067-22.4256 62.805333-68.608-0.8704-44.407467-22.016-67.054933-63.453866-67.925334h-40.994134v136.533334h41.642667z"
							 fill="#4e9bff" p-id="4456" data-spm-anchor-id="a313x.7781069.0.i5" class=""></path>
						</svg>
						<text>RFID录入</text>
					</view>
				</view>
			</view>
			<view class="WuLianWangYuanChengJianKong">
				<view class="wulianwangyuanchengjiankong_bar">
					<text>物联网远程监控</text>
				</view>
				<view class="wulianwangyuanchengjiankong_content">
					<view class="wulianwangyuanchengjiankong_content_item">
						<image src="https://i.postimg.cc/RZMzfNxB/jianzhuwu.png" mode="aspectFit"></image>
					</view>
					<view class="wulianwangyuanchengjiankong_content_item">
						<image src="https://i.postimg.cc/65xKWMHT/xiaokongshizhiban.png" mode="aspectFit"></image>
					</view>
					<view class="wulianwangyuanchengjiankong_content_item">
						<image src="https://i.postimg.cc/c1nZGpBV/fanghuoxuncha.png" mode="aspectFit"></image>
					</view>
					<view class="wulianwangyuanchengjiankong_content_item">
						<image src="https://i.postimg.cc/9FPhrySb/zhongdianbuwei.png" mode="aspectFit"></image>
					</view>
				</view>
			</view>
			<u-divider>没有更多了</u-divider>
		</view>

		<!-- tabbar  ， 与包裹页面所有内容的元素u-page同级，且在它的下方 -->
		<!-- <u-tabbar v-model="current" :list="list" :mid-button="false"></u-tabbar> -->
	</view>
</template>

<script>
	export default {
		data() {
			return {
				list: [{
						iconPath: "home",
						selectedIconPath: "home-fill",
						text: '首页',
						count: 1,
						isDot: true,
						customIcon: false,
					},
					{
						iconPath: "map",
						selectedIconPath: "map-fill",
						text: '地图',
						customIcon: false,
					},
					// {
					// 	iconPath: "https://cdn.uviewui.com/uview/common/min_button.png",
					// 	selectedIconPath: "https://cdn.uviewui.com/uview/common/min_button_select.png",
					// 	text: '发布',
					// 	midButton: true,
					// 	customIcon: false,
					// },
					{
						iconPath: "calendar",
						selectedIconPath: "calendar-fill",
						text: '维保',
						count: 1,
						isDot: true,
						customIcon: false,
					},
					{
						iconPath: "account",
						selectedIconPath: "account-fill",
						text: '我的',
						// count: 1,
						// isDot: true,
						customIcon: false,
					},
				],
				current: 0
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.home_content {
		margin-bottom: 20rpx;

		.username_bar {
			display: flex;
			justify-content: space-between;
			height: 70rpx;
			line-height: 70rpx;
			padding: 0 15rpx;
			text {
				font-size: 30rpx;
			}
			view {
				text {
					display: inline-block;
					margin-right: 20rpx;
					font-style: italic
				}
			}
			uni-view {
				vertical-align: middle;
			}
		}

		image {
			width: 100%;
			height: 100%;
		}

		.work_function {
			display: flex;
			justify-content: space-between;
			padding: 25rpx 35rpx;

			text {
				font-size: 28rpx;
			}

			.work_function_item {
				display: flex;
				flex-direction: column;
				justify-content: space-between;

				svg {
					display: block;
					margin: 0 auto;
				}

			}
		}

		.medium_image {
			width: 750rpx;
			height: 200rpx;
		}

		.ShiShiJianCe {
			.shishijiance_bar {
				display: flex;
				justify-content: space-between;
				height: 50rpx;
				line-height: 50rpx;
				padding: 5rpx 15rpx;

				text {
					font-size: 30rpx;
				}

				view {
					text {
						display: inline-block;
						margin-right: 10rpx;
					}
				}
			}

			.shishijiance_content {
				display: flex;
				justify-content: space-around;

				.shishijiance_content_item {
					display: flex;
					flex-direction: column;
					justify-content: space-between;
					margin: 10rpx 0;

					text {
						text-align: center;
					}

					text:nth-child(1) {
						font-size: 50rpx;
						padding: 10rpx;
					}
				}
			}
		}

		.WeiBaoXunCha {
			.weibaoxuncha_bar {
				height: 50rpx;
				line-height: 50rpx;
				padding: 5rpx 15rpx;

				text {
					font-size: 30rpx;
				}
			}

			.weibaoxuncha_content {
				display: flex;
				justify-content: space-between;
				padding: 25rpx 35rpx;

				text {
					font-size: 28rpx;
				}

				.weibaoxuncha_content_item {
					display: flex;
					flex-direction: column;
					justify-content: space-between;

					svg {
						display: block;
						margin: 0 auto;
					}
				}

			}
		}

		.WuLianWangYuanChengJianKong {
			.wulianwangyuanchengjiankong_bar {
				height: 50rpx;
				line-height: 50rpx;
				padding: 5rpx 15rpx;

				text {
					font-size: 30rpx;
				}
			}

			.wulianwangyuanchengjiankong_content {
				display: flex;
				justify-content: space-between;
				flex-wrap: wrap;
				padding: 5rpx 15rpx;

				.wulianwangyuanchengjiankong_content_item {
					image {
						width: 94%;
						// transform: translateX(3%);
						// display: block;
						width: 355rpx;
						height: 230rpx;
					}
				}
			}
		}
	}
</style>
