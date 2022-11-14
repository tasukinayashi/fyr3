<?php
/**
 * 罗杰nice WeChat Public Platform
 * 微信公众号 PHP 版推送信息
 *不会搞得＋QQ群 808208088
 * @copyright  Copyright (c) 2022 罗杰nice  (http://lj520lj.com)
 * @page      配置页
 */

/** 开启 Session 配置 */
session_start();
require 'function.php';

/** 微信公众号信息配置 */
$WXconfig=array(
	'app_id' => 'wxe9fbc2f69b50dcc3', //公众号appId
	'app_secret' => '885a16e569fba2f9a3c16cdd08fb1f62', //公众号appSecret
	'template_id' => 't6QO1sr1q9fULGQPQH5lt89qKtijLjLZA0LA8OtsMYU', //模板消息id
	'user' => array('oTClk6DeNMSISe63_rUm0dlqtrF4') //接收公众号消息的微信号，如果有多个，需要创建多个目录。
);

/** 微信程序信息配置 ,所有信息要填到''内*/
$INFOconfig=array(
	'region' => '广州', //所在地区，可为城市，区，县，同时支持国外城市，只可填城市不能填省。
	'birthday1' => array('name'=>'润润子','birthday'=>'2023-5-29'), //修改名字为对应需要显示的名字，生日为公历哦~ 格式：2022-8-3
	'birthday2' => array('name'=>'小栋栋','birthday'=>'2023-9-6'), //同上
	'love_date'=>'2022-2-1', //恋爱时间，填时间
        "note_ch"=>'', // 
	"note_en"=>'' //金句英文
);
	
