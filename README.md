<h3>LicenseServer-intellij plugin</h3>
<ul>
  <li>Install as a jetbrains plugin</li>
  <li>(Ignore if configured)Download<a href="https://gitee.com/ja-netfilter/ja-netfilter">ja-netfilter</a>,then configure javaagent to your ide vmOptions file.</li>
  <li>Open License server Action(ctrl+shift+alt+m or in Help Menu) to (important)[Add power param] (Ignore if configured)[add url,dns param],then restart ide.</li>
  <li>License server: <a href="http://localhost:63320/">http://localhost:63320/</a></li>
  <li>Default Config params index: <a href="http://localhost:63320/">http://localhost:63320/</a></li>
  <li>Port config in Registry(ctrl+alt+shift+/)</li>
  <li>The paid plugin product code will be displayed in the Action (must be downloaded and installed), and this code can be configured according to the rules in <Code> Settings-> License Server-> Activity </code></li>
  <li>Use the generate code in action to generate the activation code</li>
</ul>

PS. you can use Add PowerParam method(in License server Action(ctrl+shift+alt+m)) to add power param automatically. You only need to select the power.conf path.<br/>
configure power param only once, unless the power param changes in the file.<br/>
The biggest flexibility of this plugin is that you can customize the information in the key, so it means that you can generate all plugin information.

<ul>
  <li>安装作为一个jetbrains插件</li>
  <li>(配置过可忽略)下载<a href="https://gitee.com/ja-netfilter/ja-netfilter">ja-netfilter</a>,然后配置javaagent到你的ide vmOptions文件.</li>
  <li>打开License server Action(ctrl+shift+alt+m 或者在help菜单栏里) (重要)[添加power参数] (添加过可忽略)[url参数 dns参数] ,然后重启ide</li>
  <li>激活服务器地址(端口可能会变): <a href="http://localhost:63320/">http://localhost:63320/</a></li>
  <li>默认配置网页: <a href="http://localhost:63320/">http://localhost:63320/</a></li>
  <li>端口配置在Registry(ctrl+alt+shift+/)</li>
  <li>在action中会显示付费的product code(必须是已经下载安装了的插件),将这个code按照<code>Settings->License server->Activation Code</code>中的规则配置即可</li>
  <li>用action中的generate code生成激活码</li>
</ul>

PS. 添加power参数可以用action(ctrl+shift+alt+m)中的Add PowerParam方法自动添加，只需要选择power.conf路径.<br/>
一次配置power永久有效,除非power参数在文件里变了.<br/>
这个插件的最大灵活性在于你可以自定义key中的信息，所以意味着你可以生成所有插件信息.
