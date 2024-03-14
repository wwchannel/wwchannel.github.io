### 1. 快速安装 Hugo

从 [Hugo Releases](https://github.com/gohugoio/hugo/releases) 上直接下载安装适合你的版本。



### 2. 快速创建网站

```bash
hugo new site myBlog
```

上面的命令将会在一个名为 `myBlog`  的文件夹中创建一个新的 hugo 站点。



### 3. 快速使用 Hugo-Theme-Jane

把这个主题克隆到 `themes` 文件夹

```bash
cd myBlog
git clone https://github.com/xianmin/hugo-theme-jane.git --depth=1 themes/jane
```

复制一些示例文本：

```bash
cp -r themes/jane/exampleSite/content ./
```

复制默认的站点设置：

```bash
cp themes/jane/exampleSite/config.toml ./
```

启动 hugo server ：

```bash
hugo server
```

打开 http://localhost:1313/ ，你将会看到一个示例网站。

### 4. 构建并上传到git pages

```bash
hugo
```

```bash
mv public doc
```