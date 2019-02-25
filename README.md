### sl-ui
sl-ui组件库

## 按钮组件
```
<view class="form-box margin-bottom">
    <view class="btn-box">
        <button class="btn-items btn-primary">提交申请</button>
    </view>
</view>
```
## 固定页面底部按钮
```
<view class="bottom-btn-box">
    <view class="btn-info" bindtap="navigateToInput">
        入驻申请
    </view>
</view>
```
## 切换tab组建
```
<view class="status-tabs">
    <view class="status-box">
        <view class="status-label open">全部</view>
        <view class="status-label">待送货</view>
        <view class="status-label">已确认</view>
        <view class="status-label">已取消</view>
    </view>
</view>
```
## 订单列表组件
```
<view class="order-items">
    <view class="items-header flex">
        <view class="flex-item">订单编号：126036803257340376</view>
        <view class=""><label class="text-primary">分配中</label></view>
    </view>
    <view class="items-body" bindtap="navigateToInfo">
        <view class="items">房东姓名：张珊珊</view>
        <view class="items">房屋地址：东区长江6路小衡街道</view>
    </view>
    <view class="items-fooder">
        <label class="lable-btn">取消</label>
        <label class="lable-btn">查看</label>
    </view>
</view>
```
## 订单状态组件
```
<view class="state-box">
    <view class="state-title">代缴押金</view>
    <view class="state-tip">押金提示状态</view>
</view>
```
## 订单详情组件
```
<view class="order-info-box">
    <view class="info-header">
        申请信息
    </view>
    <view class="info-body">
        <view class="info-items flex">
            <view class="title">房东姓名</view>
            <view class="text flex-item">李珊珊</view>
        </view>
        <view class="info-items flex">
            <view class="title">联系电话</view>
            <view class="text flex-item"><label class="text-primary">1342003194</label></view>
        </view>
        <view class="info-items flex">
            <view class="title">房屋地址 </view>
            <view class="text flex-item">东区镇独立区自由街道11号</view>
        </view>
        <view class="info-items flex">
            <view class="title">安装推荐码</view>
            <view class="text flex-item">EF283721</view>
        </view>
    </view>
</view>
```
## 输入页面组件
```
<view class="input-box">
    <view class="input-items flex">
        <view class="title ">
            房东姓名
        </view>
        <view class="text flex-item">
            <input type="text" placeholder="输入联系人姓名"></input>
        </view>
    </view>
    <view class="input-items flex">
        <view class="title ">
            故障照片
        </view>
        <view class="text flex-item">
            <view class="img-box">
                <image class="img" src="http://pmr3uqnhr.bkt.clouddn.com/%E8%95%83%E8%8C%84%E7%A7%9F%E5%AE%9A%E6%B0%94%E8%A7%84%E6%A0%BC3.png" mode="widthFix"></image>
                <image class="img" src="http://pmr3uqnhr.bkt.clouddn.com/%E8%95%83%E8%8C%84%E7%A7%9F%E5%AE%9A%E6%B0%94%E8%A7%84%E6%A0%BC3.png" mode="widthFix"></image>
            </view>
        </view>
    </view>
    <view class="input-items flex">
        <view class="title ">
            房屋地址
        </view>
        <view class="text flex-item">
            <input type="text" placeholder="地址格式：XX镇XX区XX街道XX号"></input>
        </view>
        <view class="icon-btn">
            <image class="icon" src="/images/icon-map.png" mode="widthFix"></image>
        </view>
    </view>
</view>
```
## 提现申请页面组件
```

<view class="wallet-box">
    <view class="items-header flex">
        <view class="title">到账方式</view>
        <view class="text flex-item">
            <view class="neme">微信钱包</view>
            <view class="dosc">2小时内到账</view>
        </view>
    </view>
    <view class="items-body">
        <view class="title">
            提现金额
        </view>
        <view class="input">
            <label class="icon">¥</label>
            <input class="money"></input>
        </view>
        <view class="dosc">可提现余额¥523.1，冻结余额¥231.1 <label class="text-primary">全部提现</label></view>
    </view>
    <view class="items-fooder">
        <view class="padding-box">
            <button class="">提现</button>
        </view>
    </view>
</view>
```
## 查询条件组件
```
<view class="filter-box">
    <view class="filter-items flex">
        <view class="items flex-item" >
            <picker class="picker-items" bindchange="bindPickerChangeTime" value="{{0}}" range="{{arraytime}}">
                <view class="picker">
                  2019年1月{{arraytime[index]}}
                </view>
            </picker>
            <wxc-icon size="28" type="arrow-down"></wxc-icon>
        </view>
        <view class="items flex-item text-right">
            <picker class="picker-items" bindchange="bindPickerChangeClass" value="{{0}}" range="{{arrayclass}}">
                <view class="picker">
                  全部类型{{arraytime[index]}}
                </view>
            </picker>
            <wxc-icon size="28" type="arrow-down"></wxc-icon>
        </view>
    </view>
</view>
```

## 操作成功页面
```
<view class="success-box">
    <view class="success-img">
        <image mode="widthFix" src="/images/icon-success.png" class="icon"></image>
    </view>
    <view class="success-title">
        申请提交成功
    </view>
    <view class="success-dos">
        平台工作人员真正积极处理中
    </view>
</view>
```
