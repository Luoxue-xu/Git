<h1>命令解析</h1>
<h2>初始化配置</h2>
<dl>
  <dt>#配置使用git仓库的人员姓名</dt>
  <dd>git config --global user.name "Your Name Comes Here"</dd>
  <dt>#配置使用git仓库的人员email</dt>
  <dd>git config --global user.email you@yourdomain.example.com</dd>
  <dt>#配置到缓存 默认15分钟</dt>
  <dd>git config --global credential.helper cache</dd>
  <dt>#修改缓存时间</dt>
  <dd>git config --global credential.helper 'cache --timeout=3600'</dd>
  <dd>git config --global color.ui true</dd>
  <dd>git config --global alias.co checkout</dd>
  <dd>git config --global alias.ci commit</dd>
  <dd>git config --global alias.st status</dd>
  <dd>git config --global alias.br branch</dd>
  <dt># 设置Editor使用textmate</dt>
  <dd>git config --global core.editor "mate -w"</dd>
  <dt>#列举所有配置</dt>
  <dd>git config -1</dd>
  <dt>#用户的git配置文件</dt>
  <dd>~/.gitconfig</dd>
</dl>
