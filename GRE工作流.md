# GRE工作流

（TODO）

## Sublime Text

### 食用说明

1. 在 Sublime 里打开Package Manager 下载 [TimeNow 插件](https://github.com/filipelinhares/timenow-sublime)。

2. 在 Sublime 菜单中打开 Key Binding (Sublime -> Preference -> Key Bindings)

3. 在customized keymap（右侧），绑定某个键盘组合到 `tn_datetime` 。语法大致如下：

   ```json
   [
       {"keys": ["shift+t"], "command": "tn_datetime"}
   ]
   ```

   


### 萌新食用说明（TODO）

[Sublime Text](https://www.sublimetext.com/) 是个很好用的文本编辑器。Sublime可以判断文件类型并提供友好的文本高亮（比如Markdown），并且提供开源插件供用户绑定快捷键使用（比如时间戳）。