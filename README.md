<h3>LicenseServer</h3>
<ul>
  <li>Install as a jetbrains plugin</li>
  <li>(Ignore if configured)Download<a href="https://gitee.com/ja-netfilter/ja-netfilter">ja-netfilter</a>,then configure javaagent to your ide vmOptions file.</li>
  <li>Open Init License server Action(ctrl+shift+alt+m or in Help Menu) to (important)[Add power param] (Ignore if configured)[add url,dns param]<br/>
  you can use Add PowerParam method(in License server Action(ctrl+shift+alt+m)) to add power param automatically. You only need to select the power.conf path.then restart ide.</li>
  <li>License server(port may change): <a href="http://localhost:63320/">http://localhost:63320/</a></li>
  <li>Default Config params index: <a href="http://localhost:63320/">http://localhost:63320/</a></li>
  <li>Port config in Registry(ctrl+alt+shift+/)</li>
  <li>The paid plugin product code will be displayed in the Action (must be downloaded and installed), and this code can be configured according to the rules in <code>Settings->License server->Activation Code</code></li>
  <li>Use generate code in action(Alt+m) to generate the activation code</li>
</ul>

PS. 
configure power param only once, unless the power param changes in the file.<br/>
The biggest flexibility of this plugin is that you can customize the information in the key, so it means that you can generate all plugin information.

<ul>
  <li>安装作为一个jetbrains插件</li>
  <li>(配置过可忽略)下载<a href="https://gitee.com/ja-netfilter/ja-netfilter">ja-netfilter</a>,然后配置javaagent到你的ide vmOptions文件.</li>
  <li>打开Init License server Action(ctrl+shift+alt+m 或者在help菜单栏里) (重要)[添加power参数] (添加过可忽略)[url参数 dns参数]<br/>
      添加power参数可以用action(ctrl+shift+alt+m)中的Add PowerParam方法自动添加，只需要选择power.conf文件路径(一般在ja-netfilter/config中).然后重启ide</li>
  <li>激活服务器地址(端口可能会变): <a href="http://localhost:63320/">http://localhost:63320/</a></li>
  <li>默认配置网页: <a href="http://localhost:63320/">http://localhost:63320/</a></li>
  <li>端口配置在Registry(ctrl+alt+shift+/)</li>
  <li>在action中会显示付费的product code(必须是已经下载安装了的插件),将这个code按照<code>Settings->License server->Activation Code</code>中的规则配置即可</li>
  <li>用action(Alt+m)中的generate code生成激活码</li>
</ul>

PS. 一次配置power永久有效,除非power参数在文件里变了.<br/>
这个插件的最大灵活性在于你可以自定义key中的信息，所以意味着你可以生成所有插件信息.

Rainbow brackets: <a href="https://github.com/Nasller/plugin-myagent/releases/tag/v1.0.0">My Plugin</a> <br/>
Download jar then put it to ja-netfilter/plugin folder,Restart ide<br/>
下载上面的项目放到ja-netfilter/plugin文件夹中,重启ide

<h3>举个激活码激活的栗子🌰</h3>
<ul>
  <li>点击IDE编辑器顶部的help选项卡 选择证书服务器</li>
  
  ![image](https://user-images.githubusercontent.com/54784104/215252036-7ca84830-6652-43e4-8dd4-418b61ea6b56.png)
  
  
  <li>证书服务器弹窗大概长这样</li>
  
  ![image](https://user-images.githubusercontent.com/54784104/215252228-df532d59-bf18-4a65-9d53-3645883c3536.png)
  
  
  <li>PRAINBOWBRACKET 把这个配置到设置的product里面。（彩虹括号）</li>
  
  ![image](https://user-images.githubusercontent.com/54784104/215252351-69d155fd-34a1-499d-a9b3-8201f60c1371.png)
  
  
  <li>然后再次打开证书服务器点Jetbrains Code。（复制许可证激活码）</li>
  
  ![image](https://user-images.githubusercontent.com/54784104/215252487-001a91de-4efc-4c06-a4df-5164d5560654.png)
  
  
  <li>粘贴到插件许可证激活码框里</li>
  
  ![image](https://user-images.githubusercontent.com/54784104/215252624-22baca7f-5b3f-4a6b-b2c8-5117057c2b86.png)
  
  
  <li>ojbk 再看相应的插件许可证信息，激活成功😎</li>
  
  ![image](https://user-images.githubusercontent.com/54784104/215252730-5cbae8ad-88e7-45cb-9185-a516501ece14.png)
  
  
  <li>其余需要许可证激活的插件也是按上面方式操作激活（激活码方式）<br/>
    只需配置完成所有需要激活的插件，复制一次许可证激活码即可用来激活所有的付费插件</li>
</ul>

jrebel插件
如果激活出现NO LICENSE FOUND字样，重装jrebel插件 或者 找到plugins\jr-ide-idea\lib\jrebel6这个插件安装目录下，一般会有两个文件jrebel.jar，jrebel-backup.jar。删掉jrebel.jar。再修改jrebel-backup.jar为jrebel.jar，重启服务<br/>
适配的版本为2022.4.2。我只在这个版本试过，其他版本未知<br/>
如果还出现这个字样那就找我974776824。
