<style>
h1, h2, h3, p, div { font-size: 12px; color: #666; }
.lx-code { padding: 10px; background: #f2f2f2; border: 1px solid #ccc; }
.lx-annotation { color: #999; }
</style>

<h1>命令解析</h1>
<h2>初始化配置</h2>
<div class="lx-code">
    <p><i class="lx-annotation"># 配置使用git仓库的人员姓名</i></p>
    <p>git config --global user.name "Your Name Comes Here"</p>
    <p><i class="lx-annotation"># 配置使用git仓库的人员email</i></p>
    <p>git config --global user.email you@yourdomain.example.com</p>
    <p><i class="lx-annotation"># 配置到缓存 默认15分钟</i></p>
    <p>git config --global credential.helper cache</p>
    <p><i class="lx-annotation"># 修改缓存时间</i></p>
    <p>git config --global credential.helper 'cache --timeout=3600'</p>
    <p>git config --global color.ui true</p>
    <p>git config --global alias.co checkout</p>
    <p>git config --global alias.ci commit</p>
    <p>git config --global alias.st status</p>
    <p>git config --global alias.br branch</p>
    <p><i class="lx-annotation"># 设置Editor使用textmate</i></p>
    <p>git config --global core.editor "mate -w"</p>
    <p><i class="lx-annotation"># 列举所有配置</i></p>
    <p>git config -1</p>
    <p><i class="lx-annotation"># 用户的git配置文件</i></p>
    <p>~/.gitconfig</p>
</div>
