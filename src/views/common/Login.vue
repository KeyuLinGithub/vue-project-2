<template>
	<div class="login">
    	
    	<div class="login-con">
	        <Card :bordered="false">
	            <p slot="title">
                    <Icon type="log-in" style="margin-right: 6px;"></Icon>欢迎登录
	            </p>
	            <div class="form-con">
					<form autocomplete="off" class="ivu-form ivu-form-label-right">
						<div class="ivu-form-item ivu-form-item-required">
							<!---->
							<div class="ivu-form-item-content">
								<div class="ivu-input-wrapper ivu-input-type ivu-input-group ivu-input-group-with-prepend">
									<div class="ivu-input-group-prepend" style="">
										<span>
											<i class="ivu-icon ivu-icon-person" style="font-size: 16px;"></i>
										</span>
									</div>
									<!----><i class="ivu-icon ivu-icon-load-c ivu-load-loop ivu-input-icon ivu-input-icon-validate"></i> 
									<input autocomplete="off" spellcheck="false" type="text" placeholder="请输入用户名" class="ivu-input">
									<!---->
								</div>
								<!---->
							</div>
						</div>
						<div class="ivu-form-item ivu-form-item-required">
							<!---->
							<div class="ivu-form-item-content">
								<div class="ivu-input-wrapper ivu-input-type ivu-input-group ivu-input-group-with-prepend">
									<div class="ivu-input-group-prepend" style="">
										<span>
											<i class="ivu-icon ivu-icon-locked" style="font-size: 14px;"></i>
										</span>
									</div>
									<!----><i class="ivu-icon ivu-icon-load-c ivu-load-loop ivu-input-icon ivu-input-icon-validate"></i> 
									<input autocomplete="off" spellcheck="false" type="password" placeholder="请输入密码" class="ivu-input">
									<!---->
								</div>
								<!---->
							</div>
						</div>
						<div class="ivu-form-item">
							<!---->
							<div class="ivu-form-item-content"><button type="button" class="ivu-btn ivu-btn-primary ivu-btn-long"><!----> <!----> <span>登录</span></button>
								<!---->
							</div>
						</div>
					</form>
					<p class="login-tip">输入任意用户名和密码即可</p>
				</div>
	        </Card>
	    </div>
    </div>
    
</template>

<script>
var Main = {
    
}

var Component = Vue.extend(Main)
new Component().$mount('#app')



</script>
</body>
</html>