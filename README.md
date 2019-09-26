# spider-flow-oss

#### 介绍
spider-flow OSS插件

#### 使用方法
在 spider-flow-web pom.xml引用
<dependency>
	<groupId>org.spiderflow</groupId>
	<artifactId>spider-flow-oss</artifactId>
	<version>0.0.1</version>
</dependency>

#### 使用操作
上传（支持两种方式）：
${resp.bytes.ossUpload('oss_id（配置的主键）','static/1.jpg')}
${'http://1.jpg'.ossUpload('oss_id（配置的主键）','static/1.jpg')}

删除：
${'static/1.jpg'.ossDelete()}