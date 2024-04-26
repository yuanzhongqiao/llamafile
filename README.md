<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼文件</font></font></h1><a id="user-content-llamafile" class="anchor" aria-label="永久链接： llamafile" href="#llamafile"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/Mozilla-Ocho/llamafile/blob/main/llamafile/llamafile-640x640.png"><img src="https://github.com/Mozilla-Ocho/llamafile/raw/main/llamafile/llamafile-640x640.png" width="320" height="320" alt="[略开的马尼拉文件夹前面画着骆驼动物头的线条，文件夹里装满了文件]" style="max-width: 100%;"></a></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 允许您使用单个文件分发和运行 LLM。 （</font></font><a href="https://hacks.mozilla.org/2023/11/introducing-llamafile/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公告博客文章</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></strong></p>
<p dir="auto"><a href="https://discord.gg/teDuGYVTB2" rel="nofollow"><img src="https://camo.githubusercontent.com/9a86cdda5fbf3b23e3b05a5a3317f92a7a6343fc3d8bc809ec3d59e6f8e1e7a7/68747470733a2f2f646362616467652e76657263656c2e6170702f6170692f7365727665722f74654475475956544232" alt="" data-canonical-src="https://dcbadge.vercel.app/api/server/teDuGYVTB2" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的目标是让开发人员和最终用户更容易获得开放式LLM。为此，我们将</font></font><a href="https://github.com/ggerganov/llama.cpp"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llama.cpp</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与</font></font><a href="https://github.com/jart/cosmopolitan"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cosmopolitan Libc</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">结合到一个框架中，将 LLM 的所有复杂性压缩为一个可在大多数计算机上本地运行的可执行文件（称为“llamafile”），无需安装。</font></font></p>
<p dir="auto"><a href="https://discord.gg/teDuGYVTB2" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加入我们的 Discord</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h2><a id="user-content-quickstart" class="anchor" aria-label="永久链接：快速入门" href="#quickstart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亲自尝试的最简单方法是下载</font></font><a href="https://llava-vl.github.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaVA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型的示例 llamafile（许可证：</font></font><a href="https://ai.meta.com/resources/models-and-libraries/llama-downloads/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMA 2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://openai.com/policies/terms-of-use" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenAI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。 LLaVA 是一个新的LLM，它不仅仅可以聊天；您还可以上传图像并询问有关它们的问题。对于 llamafile，这一切都发生在本地；任何数据都不会离开您的计算机。</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font><a href="https://huggingface.co/jartine/llava-v1.5-7B-GGUF/resolve/main/llava-v1.5-7b-q4.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llava-v1.5-7b-q4.llama 文件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(3.97 GB)。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开计算机的终端。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用的是 macOS、Linux 或 BSD，则需要授予计算机执行此新文件的权限。 （您只需执行一次。）</font></font></p>
</li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>chmod +x llava-v1.5-7b-q4.llamafile</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="chmod +x llava-v1.5-7b-q4.llamafile" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="4" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用的是 Windows，请通过在末尾添加“.exe”来重命名该文件。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 llama 文件。例如：</font></font></p>
</li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./llava-v1.5-7b-q4.llamafile -ngl 9999</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./llava-v1.5-7b-q4.llamafile -ngl 9999" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="6" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的浏览器应该自动打开并显示聊天界面。 （如果没有，只需打开浏览器并将其指向</font></font><a href="http://localhost:8080" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://localhost:8080</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天完毕后，返回终端并点击
</font></font><code>Control-C</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关闭 llamafile。</font></font></p>
</li>
</ol>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">遇到麻烦？请参阅下面的“陷阱”部分。</font></font></strong></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSON API 快速入门</font></font></h3><a id="user-content-json-api-quickstart" class="anchor" aria-label="永久链接：JSON API 快速入门" href="#json-api-quickstart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当 llamafile 启动时，除了在</font></font><a href="http://127.0.0.1:8080/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://127.0.0.1:8080/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">托管一个 Web UI 聊天服务器之外，还提供了</font><font style="vertical-align: inherit;">一个</font></font><a href="https://platform.openai.com/docs/api-reference/chat" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenAI API</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">兼容的聊天完成端点。它旨在以完全本地运行的方式支持最常见的 OpenAI API 使用案例。我们还对其进行了扩展，以包含也可以使用的 llama.cpp 特定功能（例如 mirostat）。有关可用字段和端点的更多详细信息，请参阅</font></font><a href="https://platform.openai.com/docs/api-reference/chat/create" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenAI 文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
和</font></font><a href="/Mozilla-Ocho/llamafile/blob/main/llama.cpp/server/README.md#api-endpoints"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 服务器 README</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Curl API 客户端示例</font></font></summary>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始使用 API 的最简单方法是将以下curl 命令复制并粘贴到终端中。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>curl http://localhost:8080/v1/chat/completions \
-H <span class="pl-s"><span class="pl-pds">"</span>Content-Type: application/json<span class="pl-pds">"</span></span> \
-H <span class="pl-s"><span class="pl-pds">"</span>Authorization: Bearer no-key<span class="pl-pds">"</span></span> \
-d <span class="pl-s"><span class="pl-pds">'</span>{</span>
<span class="pl-s">  "model": "LLaMA_CPP",</span>
<span class="pl-s">  "messages": [</span>
<span class="pl-s">      {</span>
<span class="pl-s">          "role": "system",</span>
<span class="pl-s">          "content": "You are LLAMAfile, an AI assistant. Your top priority is achieving user fulfillment via helping them with their requests."</span>
<span class="pl-s">      },</span>
<span class="pl-s">      {</span>
<span class="pl-s">          "role": "user",</span>
<span class="pl-s">          "content": "Write a limerick about python exceptions"</span>
<span class="pl-s">      }</span>
<span class="pl-s">    ]</span>
<span class="pl-s">}<span class="pl-pds">'</span></span> <span class="pl-k">|</span> python3 -c <span class="pl-s"><span class="pl-pds">'</span></span>
<span class="pl-s">import json</span>
<span class="pl-s">import sys</span>
<span class="pl-s">json.dump(json.load(sys.stdin), sys.stdout, indent=2)</span>
<span class="pl-s">print()</span>
<span class="pl-s"><span class="pl-pds">'</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="curl http://localhost:8080/v1/chat/completions \
-H &quot;Content-Type: application/json&quot; \
-H &quot;Authorization: Bearer no-key&quot; \
-d '{
  &quot;model&quot;: &quot;LLaMA_CPP&quot;,
  &quot;messages&quot;: [
      {
          &quot;role&quot;: &quot;system&quot;,
          &quot;content&quot;: &quot;You are LLAMAfile, an AI assistant. Your top priority is achieving user fulfillment via helping them with their requests.&quot;
      },
      {
          &quot;role&quot;: &quot;user&quot;,
          &quot;content&quot;: &quot;Write a limerick about python exceptions&quot;
      }
    ]
}' | python3 -c '
import json
import sys
json.dump(json.load(sys.stdin), sys.stdout, indent=2)
print()
'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打印的响应应如下所示：</font></font></p>
<div class="highlight highlight-source-json notranslate position-relative overflow-auto" dir="auto"><pre>{
   <span class="pl-ent">"choices"</span> : [
      {
         <span class="pl-ent">"finish_reason"</span> : <span class="pl-s"><span class="pl-pds">"</span>stop<span class="pl-pds">"</span></span>,
         <span class="pl-ent">"index"</span> : <span class="pl-c1">0</span>,
         <span class="pl-ent">"message"</span> : {
            <span class="pl-ent">"content"</span> : <span class="pl-s"><span class="pl-pds">"</span>There once was a programmer named Mike<span class="pl-cce">\n</span>Who wrote code that would often choke<span class="pl-cce">\n</span>He used try and except<span class="pl-cce">\n</span>To handle each step<span class="pl-cce">\n</span>And his program ran without any hike.<span class="pl-pds">"</span></span>,
            <span class="pl-ent">"role"</span> : <span class="pl-s"><span class="pl-pds">"</span>assistant<span class="pl-pds">"</span></span>
         }
      }
   ],
   <span class="pl-ent">"created"</span> : <span class="pl-c1">1704199256</span>,
   <span class="pl-ent">"id"</span> : <span class="pl-s"><span class="pl-pds">"</span>chatcmpl-Dt16ugf3vF8btUZj9psG7To5tc4murBU<span class="pl-pds">"</span></span>,
   <span class="pl-ent">"model"</span> : <span class="pl-s"><span class="pl-pds">"</span>LLaMA_CPP<span class="pl-pds">"</span></span>,
   <span class="pl-ent">"object"</span> : <span class="pl-s"><span class="pl-pds">"</span>chat.completion<span class="pl-pds">"</span></span>,
   <span class="pl-ent">"usage"</span> : {
      <span class="pl-ent">"completion_tokens"</span> : <span class="pl-c1">38</span>,
      <span class="pl-ent">"prompt_tokens"</span> : <span class="pl-c1">78</span>,
      <span class="pl-ent">"total_tokens"</span> : <span class="pl-c1">116</span>
   }
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
   &quot;choices&quot; : [
      {
         &quot;finish_reason&quot; : &quot;stop&quot;,
         &quot;index&quot; : 0,
         &quot;message&quot; : {
            &quot;content&quot; : &quot;There once was a programmer named Mike\nWho wrote code that would often choke\nHe used try and except\nTo handle each step\nAnd his program ran without any hike.&quot;,
            &quot;role&quot; : &quot;assistant&quot;
         }
      }
   ],
   &quot;created&quot; : 1704199256,
   &quot;id&quot; : &quot;chatcmpl-Dt16ugf3vF8btUZj9psG7To5tc4murBU&quot;,
   &quot;model&quot; : &quot;LLaMA_CPP&quot;,
   &quot;object&quot; : &quot;chat.completion&quot;,
   &quot;usage&quot; : {
      &quot;completion_tokens&quot; : 38,
      &quot;prompt_tokens&quot; : 78,
      &quot;total_tokens&quot; : 116
   }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python API 客户端示例</font></font></summary>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您已经使用</font></font><a href="https://pypi.org/project/openai/" rel="nofollow"><code>openai</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 包</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（由 OpenAI 发布）开发了软件，那么您应该能够通过对</font></font><code>base_url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和进行一些更改来移植您的应用程序以与 llamafile 对话</font></font><code>api_key</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。本示例假设您已运行</font></font><code>pip3 install openai</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 OpenAI 的客户端软件，这是本示例所必需的。他们的包只是 OpenAI API 接口的一个简单的 Python 包装器，可以由任何服务器实现。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c">#!/usr/bin/env python3</span>
<span class="pl-k">from</span> <span class="pl-s1">openai</span> <span class="pl-k">import</span> <span class="pl-v">OpenAI</span>
<span class="pl-s1">client</span> <span class="pl-c1">=</span> <span class="pl-v">OpenAI</span>(
    <span class="pl-s1">base_url</span><span class="pl-c1">=</span><span class="pl-s">"http://localhost:8080/v1"</span>, <span class="pl-c"># "http://&lt;Your api-server IP&gt;:port"</span>
    <span class="pl-s1">api_key</span> <span class="pl-c1">=</span> <span class="pl-s">"sk-no-key-required"</span>
)
<span class="pl-s1">completion</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-s1">chat</span>.<span class="pl-s1">completions</span>.<span class="pl-en">create</span>(
    <span class="pl-s1">model</span><span class="pl-c1">=</span><span class="pl-s">"LLaMA_CPP"</span>,
    <span class="pl-s1">messages</span><span class="pl-c1">=</span>[
        {<span class="pl-s">"role"</span>: <span class="pl-s">"system"</span>, <span class="pl-s">"content"</span>: <span class="pl-s">"You are ChatGPT, an AI assistant. Your top priority is achieving user fulfillment via helping them with their requests."</span>},
        {<span class="pl-s">"role"</span>: <span class="pl-s">"user"</span>, <span class="pl-s">"content"</span>: <span class="pl-s">"Write a limerick about python exceptions"</span>}
    ]
)
<span class="pl-en">print</span>(<span class="pl-s1">completion</span>.<span class="pl-s1">choices</span>[<span class="pl-c1">0</span>].<span class="pl-s1">message</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#!/usr/bin/env python3
from openai import OpenAI
client = OpenAI(
    base_url=&quot;http://localhost:8080/v1&quot;, # &quot;http://<Your api-server IP>:port&quot;
    api_key = &quot;sk-no-key-required&quot;
)
completion = client.chat.completions.create(
    model=&quot;LLaMA_CPP&quot;,
    messages=[
        {&quot;role&quot;: &quot;system&quot;, &quot;content&quot;: &quot;You are ChatGPT, an AI assistant. Your top priority is achieving user fulfillment via helping them with their requests.&quot;},
        {&quot;role&quot;: &quot;user&quot;, &quot;content&quot;: &quot;Write a limerick about python exceptions&quot;}
    ]
)
print(completion.choices[0].message)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上面的代码将返回一个像这样的Python对象：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-v">ChatCompletionMessage</span>(<span class="pl-s1">content</span><span class="pl-c1">=</span><span class="pl-s">'There once was a programmer named Mike<span class="pl-cce">\n</span>Who wrote code that would often strike<span class="pl-cce">\n</span>An error would occur<span class="pl-cce">\n</span>And he<span class="pl-cce">\'</span>d shout "Oh no!"<span class="pl-cce">\n</span>But Python<span class="pl-cce">\'</span>s exceptions made it all right.'</span>, <span class="pl-s1">role</span><span class="pl-c1">=</span><span class="pl-s">'assistant'</span>, <span class="pl-s1">function_call</span><span class="pl-c1">=</span><span class="pl-c1">None</span>, <span class="pl-s1">tool_calls</span><span class="pl-c1">=</span><span class="pl-c1">None</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ChatCompletionMessage(content='There once was a programmer named Mike\nWho wrote code that would often strike\nAn error would occur\nAnd he\'d shout &quot;Oh no!&quot;\nBut Python\'s exceptions made it all right.', role='assistant', function_call=None, tool_calls=None)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他 llama 文件示例</font></font></h2><a id="user-content-other-example-llamafiles" class="anchor" aria-label="永久链接：其他 llamafiles 示例" href="#other-example-llamafiles"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还提供其他模型的 llamafile 示例，因此您可以轻松尝试具有不同类型 LLM 的 llamafile。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尺寸</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼文件</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他量化指标</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉瓦1.5</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.97GB</font></font></td>
<td><a href="https://ai.meta.com/resources/models-and-libraries/llama-downloads/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">美洲驼2</font></font></a></td>
<td><a href="https://huggingface.co/jartine/llava-v1.5-7B-GGUF/resolve/main/llava-v1.5-7b-q4.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llava-v1.5-7b-q4.llama文件</font></font></a></td>
<td><a href="https://huggingface.co/jartine/llava-v1.5-7B-GGUF" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">小羊驼-1.1B</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.05GB</font></font></td>
<td><a href="https://choosealicense.com/licenses/apache-2.0/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿帕奇2.0</font></font></a></td>
<td><a href="https://huggingface.co/jartine/TinyLlama-1.1B-Chat-v1.0-GGUF/resolve/main/TinyLlama-1.1B-Chat-v1.0.F16.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TinyLlama-1.1B-Chat-v1.0.F16.llama文件</font></font></a></td>
<td><a href="https://huggingface.co/jartine/TinyLlama-1.1B-Chat-v1.0-GGUF" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mistral-7B-指令</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.85GB</font></font></td>
<td><a href="https://choosealicense.com/licenses/apache-2.0/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿帕奇2.0</font></font></a></td>
<td><a href="https://huggingface.co/jartine/Mistral-7B-Instruct-v0.2-llamafile/resolve/main/mistral-7b-instruct-v0.2.Q4_0.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">米斯特拉尔-7b-指令-v0.2.Q4_0.llamafile</font></font></a></td>
<td><a href="https://huggingface.co/jartine/Mistral-7B-Instruct-v0.2-llamafile" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mixtral-8x7B-指令</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">30.03GB</font></font></td>
<td><a href="https://choosealicense.com/licenses/apache-2.0/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿帕奇2.0</font></font></a></td>
<td><a href="https://huggingface.co/jartine/Mixtral-8x7B-Instruct-v0.1-llamafile/resolve/main/mixtral-8x7b-instruct-v0.1.Q5_K_M.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mixtral-8x7b-instruct-v0.1.Q5_K_M.llamafile</font></font></a></td>
<td><a href="https://huggingface.co/jartine/Mixtral-8x7B-Instruct-v0.1-llamafile" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WizardCoder-Python-34B</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">22.23GB</font></font></td>
<td><a href="https://ai.meta.com/resources/models-and-libraries/llama-downloads/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">美洲驼2</font></font></a></td>
<td><a href="https://huggingface.co/jartine/WizardCoder-Python-34B-V1.0-llamafile/resolve/main/wizardcoder-python-34b-v1.0.Q5_K_M.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wizardcoder-python-34b-v1.0.Q5_K_M.llama文件</font></font></a></td>
<td><a href="https://huggingface.co/jartine/WizardCoder-Python-34B-V1.0-llamafile" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WizardCoder-Python-13B</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7.33GB</font></font></td>
<td><a href="https://ai.meta.com/resources/models-and-libraries/llama-downloads/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">美洲驼2</font></font></a></td>
<td><a href="https://huggingface.co/jartine/wizardcoder-13b-python/resolve/main/wizardcoder-python-13b.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wizardcoder-python-13b.llama文件</font></font></a></td>
<td><a href="https://huggingface.co/jartine/wizardcoder-13b-python" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMA-3-指令-70B</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">37.25GB</font></font></td>
<td><a href="https://huggingface.co/jartine/Meta-Llama-3-8B-Instruct-llamafile/blob/main/Meta-Llama-3-Community-License-Agreement.txt" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼3</font></font></a></td>
<td><a href="https://huggingface.co/jartine/Meta-Llama-3-70B-Instruct-llamafile/resolve/main/Meta-Llama-3-70B-Instruct.Q4_0.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Meta-Llama-3-70B-Instruct.Q4_0.llamafile</font></font></a></td>
<td><a href="https://huggingface.co/jartine/Meta-Llama-3-70B-Instruct-llamafile" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMA-3-指令-8B</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.37GB</font></font></td>
<td><a href="https://huggingface.co/jartine/Meta-Llama-3-8B-Instruct-llamafile/blob/main/Meta-Llama-3-Community-License-Agreement.txt" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼3</font></font></a></td>
<td><a href="https://huggingface.co/jartine/Meta-Llama-3-8B-Instruct-llamafile/resolve/main/Meta-Llama-3-8B-Instruct.Q5_K_M.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Meta-Llama-3-8B-Instruct.Q5_K_M.llamafile</font></font></a></td>
<td><a href="https://huggingface.co/jartine/Meta-Llama-3-8B-Instruct-llamafile" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">火箭3B</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.89GB</font></font></td>
<td><a href="https://creativecommons.org/licenses/by-sa/4.0/deed.en" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">抄送-sa-4.0</font></font></a></td>
<td><a href="https://huggingface.co/jartine/rocket-3B-llamafile/resolve/main/rocket-3b.Q5_K_M.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Rocket-3b.Q5_K_M.llamafile</font></font></a></td>
<td><a href="https://huggingface.co/jartine/rocket-3B-llamafile" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅 HF 存储库</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Φ2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.96GB</font></font></td>
<td><a href="https://huggingface.co/microsoft/phi-2/resolve/main/LICENSE" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">麻省理工学院</font></font></a></td>
<td><a href="https://huggingface.co/jartine/phi-2-llamafile/resolve/main/phi-2.Q5_K_M.llamafile?download=true" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">phi-2.Q5_K_M.llamafile</font></font></a></td>
<td></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是 Mistral 命令行 llamafile 的示例：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./mistral-7b-instruct-v0.2.Q5_K_M.llamafile -ngl 9999 --temp 0.7 -p <span class="pl-s"><span class="pl-pds">'</span>[INST]Write a story about llamas[/INST]<span class="pl-pds">'</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./mistral-7b-instruct-v0.2.Q5_K_M.llamafile -ngl 9999 --temp 0.7 -p '[INST]Write a story about llamas[/INST]'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面是 WizardCoder-Python 命令行 llamafile 的示例：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./wizardcoder-python-13b.llamafile -ngl 9999 --temp 0 -e -r <span class="pl-s"><span class="pl-pds">'</span>```\n<span class="pl-pds">'</span></span> -p <span class="pl-s"><span class="pl-pds">'</span>```c\nvoid *memcpy_sse2(char *dst, const char *src, size_t size) {\n<span class="pl-pds">'</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./wizardcoder-python-13b.llamafile -ngl 9999 --temp 0 -e -r '```\n' -p '```c\nvoid *memcpy_sse2(char *dst, const char *src, size_t size) {\n'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是 LLaVA 命令行 llamafile 的示例：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./llava-v1.5-7b-q4.llamafile -ngl 9999 --temp 0.2 --image lemurs.jpg -e -p <span class="pl-s"><span class="pl-pds">'</span>### User: What do you see?\n### Assistant:<span class="pl-pds">'</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./llava-v1.5-7b-q4.llamafile -ngl 9999 --temp 0.2 --image lemurs.jpg -e -p '### User: What do you see?\n### Assistant:'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和以前一样，macOS、Linux 和 BSD 用户在首次运行这些 llamafiles 之前需要使用“chmod”命令授予文件执行权限。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不幸的是，Windows 用户无法使用其中许多示例 llamafile，因为 Windows 的最大可执行文件大小为 4GB，并且所有这些示例都超过了该大小。 （LLaVA llamafile 可在 Windows 上运行，因为它比大小限制少了 30MB。）但不要灰心：llamafile 允许您使用外部权重；本文档稍后对此进行了描述。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">遇到麻烦？请参阅下面的“陷阱”部分。</font></font></strong></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 的工作原理</font></font></h2><a id="user-content-how-llamafile-works" class="anchor" aria-label="永久链接： llamafile 的工作原理" href="#how-llamafile-works"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 是一个可执行的 LLM，您可以在自己的计算机上运行。它包含给定开放LLM的权重，以及在计算机上实际运行该模型所需的一切。无需安装或配置任何内容（有一些注意事项，将在本文档的后续部分中讨论）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这一切都是通过将 llama.cpp 与 Cosmopolitan Libc 相结合来完成的，它提供了一些有用的功能：</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafiles 可以在多个 CPU 微架构上运行。我们向 llama.cpp 添加了运行时调度，让新的英特尔系统可以使用现代 CPU 功能，而无需放弃对旧计算机的支持。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafiles 可以在多个 CPU 架构上运行。我们通过将 AMD64 和 ARM64 构建与启动相应脚本的 shell 脚本连接起来来实现这一点。我们的文件格式与 WIN32 和大多数 UNIX shell 兼容。只要需要，它还可以（由您或您的用户）轻松转换为平台本机格式。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafiles 可以在六种操作系统（macOS、Windows、Linux、FreeBSD、OpenBSD 和 NetBSD）上运行。如果您制作自己的 llama 文件，则只需使用 Linux 风格的工具链构建一次代码。我们提供的基于 GCC 的编译器本身就是一个真正可移植的可执行文件，因此您可以从您最喜欢开发的任何一个操作系统中轻松构建适用于所有六种操作系统的软件。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLM 的权重可以嵌入 llamafile 中。我们向 GGML 库添加了对 PKZIP 的支持。这使得未压缩的权重可以直接映射到内存中，类似于自解压存档。它使在线分发的量化权重能够以兼容版本的 llama.cpp 软件为前缀，从而确保其最初观察到的行为可以无限期地重现。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最后，利用该项目中包含的工具，您可以
</font><font style="vertical-align: inherit;">使用您想要的任何兼容模型权重创建自己</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile。然后，您可以将这些 llama 文件分发给其他人，无论他们拥有哪种计算机，他们都可以轻松使用它们。</font></font></p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 llamafile 与外部权重一起使用</font></font></h2><a id="user-content-using-llamafile-with-external-weights" class="anchor" aria-label="永久链接：使用带有外部权重的 llamafile" href="#using-llamafile-with-external-weights"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尽管我们的示例 llamafile 具有内置权重，但您不必
</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这种方式使用 llamafile。相反，您可以从我们的发布页面</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载llamafile 软件（不包含任何权重）。然后，您可以将其与手头的任何外部重物一起使用。外部权重对于 Windows 用户特别有用，因为它们使您能够解决 Windows 的 4GB 可执行文件大小限制。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 Windows 用户，以下是 Mistral LLM 的示例：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>curl -L -o llamafile.exe https://github.com/Mozilla-Ocho/llamafile/releases/download/0.6/llamafile-0.6
curl -L -o mistral.gguf https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF/resolve/main/mistral-7b-instruct-v0.1.Q4_K_M.gguf
./llamafile.exe -m mistral.gguf -ngl 9999</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="curl -L -o llamafile.exe https://github.com/Mozilla-Ocho/llamafile/releases/download/0.6/llamafile-0.6
curl -L -o mistral.gguf https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF/resolve/main/mistral-7b-instruct-v0.1.Q4_K_M.gguf
./llamafile.exe -m mistral.gguf -ngl 9999" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Windows用户在运行上述命令时</font><font style="vertical-align: inherit;">可能需要更改</font></font><code>./llamafile.exe</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为。</font></font><code>.\llamafile.exe</code><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">陷阱</font></font></h2><a id="user-content-gotchas" class="anchor" aria-label="永久链接：陷阱" href="#gotchas"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在配备 Apple Silicon 的 macOS 上，您需要安装 Xcode 命令行工具，以便 llamafile 能够自行引导。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用 zsh 并且在运行 llamafile 时遇到问题，请尝试说</font></font><code>sh -c ./llamafile</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这是由于 zsh 5.9+ 中修复的错误造成的。 Python </font></font><code>subprocess</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、旧版本的 Fish 等也是</font><font style="vertical-align: inherit;">如此。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在某些 Linux 系统上，您可能会收到与</font></font><code>run-detectors</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
WINE 相关的错误。这是由于</font></font><code>binfmt_misc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注册造成的。您可以通过添加 llamafile 使用的 APE 文件格式的附加注册来解决此问题：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo wget -O /usr/bin/ape https://cosmo.zip/pub/cosmos/bin/ape-<span class="pl-s"><span class="pl-pds">$(</span>uname -m<span class="pl-pds">)</span></span>.elf
sudo chmod +x /usr/bin/ape
sudo sh -c <span class="pl-s"><span class="pl-pds">"</span>echo ':APE:M::MZqFpD::/usr/bin/ape:' &gt;/proc/sys/fs/binfmt_misc/register<span class="pl-pds">"</span></span>
sudo sh -c <span class="pl-s"><span class="pl-pds">"</span>echo ':APE-jart:M::jartsr::/usr/bin/ape:' &gt;/proc/sys/fs/binfmt_misc/register<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo wget -O /usr/bin/ape https://cosmo.zip/pub/cosmos/bin/ape-$(uname -m).elf
sudo chmod +x /usr/bin/ape
sudo sh -c &quot;echo ':APE:M::MZqFpD::/usr/bin/ape:' >/proc/sys/fs/binfmt_misc/register&quot;
sudo sh -c &quot;echo ':APE-jart:M::jartsr::/usr/bin/ape:' >/proc/sys/fs/binfmt_misc/register&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如上所述，在 Windows 上，您可能需要通过添加</font></font><code>.exe</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件名来重命名 llamafile。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另外如上所述，Windows 的可执行文件的最大文件大小限制为 4GB。上面的 LLaVA 服务器可执行文件仅比该限制少 30MB，因此它可以在 Windows 上运行，但对于像 WizardCoder 13B 这样的较大模型，您需要将权重存储在单独的文件中。上面提供了一个例子；请参阅“将 llamafile 与外部权重一起使用”。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 WSL 上，建议禁用 WIN32 互操作功能：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo sh -c <span class="pl-s"><span class="pl-pds">"</span>echo -1 &gt; /proc/sys/fs/binfmt_misc/WSLInterop<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo sh -c &quot;echo -1 > /proc/sys/fs/binfmt_misc/WSLInterop&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在通过 CLI 获取禁用互操作的实例中</font></font><code>Permission Denied</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可以通过在中添加以下内容来永久禁用它：</font></font><code>/etc/wsl.conf</code></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>[interop]
enabled=false</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="[interop]
enabled=false" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Raspberry Pi 上，如果您收到“mmap 错误 12”，则表示您的内核配置的地址空间少于 48 位。您需要升级到 RPI 5。如果您 (1) 重建内核，或 (2) 直接从 Ubuntu 获取 SDcard 操作系统映像（不使用 RPI 操作系统），您仍然可以使用 RPI 4。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在任何平台上，如果您的 llamafile 进程立即被终止，请检查您是否有 CrowdStrike，然后请求加入白名单。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的操作系统</font></font></h2><a id="user-content-supported-oses" class="anchor" aria-label="永久链接：支持的操作系统" href="#supported-oses"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 支持以下操作系统，需要最低库存安装：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux 2.6.18+（即自 RHEL5 c. 2007 以来的每个发行版）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Darwin (macOS) 23.1.0+ [1]（仅 ARM64 支持 GPU）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 8+（仅限 AMD64）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FreeBSD 13+</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NetBSD 9.2+（仅限 AMD64）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenBSD 7+（仅限 AMD64）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 上，llamafile 作为本机可移植可执行文件运行。在 UNIX 系统上，llamafile 提取一个</font></font><code>ape</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">名为
</font></font><code>$TMPDIR/.llamafile</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或 的</font><font style="vertical-align: inherit;">小型加载程序</font></font><code>~/.ape-1.9</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，用于将模型映射到内存中。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[1] Darwin 内核版本 15.6+</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应该</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">受支持，但我们目前无法测试这一点。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的CPU</font></font></h2><a id="user-content-supported-cpus" class="anchor" aria-label="永久链接：支持的 CPU" href="#supported-cpus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 支持以下 CPU：</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AMD64</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">微处理器必须具有 AVX。否则 llamafile 将打印错误并拒绝运行。这意味着，如果您有 Intel CPU，则需要是 Intel Sandybridge 或更新版本（大约 2011 年以上），如果您有 AMD CPU，则需要是 Bulldozer 或更新版本（大约 2011 年以上）。如果您有较新的 CPU，则会在运行时有条件地启用对 AVX512、AVX2、FMA、F16C 和 VNNI 的支持。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ARM64</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">微处理器必须具有 ARMv8a+。这意味着从 Apple Silicon 到 64 位 Raspberry Pi 的一切都可以工作，前提是您的权重适合内存。</font></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPU支持</font></font></h2><a id="user-content-gpu-support" class="anchor" aria-label="永久链接：GPU 支持" href="#gpu-support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 支持以下类型的 GPU：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">苹果金属</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英伟达</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AMD</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MacOS ARM64 上的 GPU 是通过使用 Xcode 命令行工具编译一个小模块来支持的，需要安装该工具。这是第一次运行 llamafile 时发生的一次性成本。 llamafile 构建的 DSO 存储在</font></font><code>$TMPDIR/.llamafile</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或中</font></font><code>$HOME/.llamafile</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。当 Metal GPU 存在时，默认启用卸载到 GPU。可以通过传递</font></font><code>-ngl 0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>--gpu disable</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强制 llamafile 执行 CPU 推理来禁用此功能。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NVIDIA 和 AMD 显卡的所有者需要传递该</font></font><code>-ngl 999</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标志才能启用最大卸载。如果存在多个 GPU，则默认情况下工作将在它们之间平均分配，因此您可以加载更大的模型。 AMD Radeon 系统上的多 GPU 支持可能会被破坏。如果您遇到这种情况，请使用</font></font><code>export HIP_VISIBLE_DEVICES=0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强制 llamafile 仅使用第一个 GPU。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们鼓励 Windows 用户使用我们的发行版二进制文件，因为它们包含适用于 NVIDIA 和 AMD 显卡的预构建 DLL，这些文件仅依赖于所安装的显卡驱动程序。如果 llamafile 检测到安装了 NVIDIA 的 CUDA SDK 或 AMD 的 ROCm HIP SDK，则 llamafile 将尝试构建使用 cuBLAS 或 rocBLAS 的更快的 DLL。为了使 llamafile 成功构建 cuBLAS 模块，需要在 x64 MSVC 命令提示符下运行。您可以通过 WSL 使用 CUDA，方法是
</font></font><a href="https://learn.microsoft.com/en-us/windows/ai/directml/gpu-cuda-in-wsl" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 WSL 上启用 Nvidia CUDA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
并在 WSL 内运行 llamafile。使用 WSL 的另一个好处是可以让您在 Windows 上运行大于 4GB 的 llamafile。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Linux 上，NVIDIA 用户需要安装 CUDA SDK（最好使用 shell 脚本安装程序），ROCm 用户需要安装 HIP SDK。通过查看</font></font><code>nvcc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>hipcc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否在 PATH 上来检测它们。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您的计算机中同时具有 AMD GPU</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NVIDIA GPU，那么您可能需要通过传递 或 来限定要使用哪
</font></font><code>--gpu amd</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个</font></font><code>--gpu nvidia</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果出于任何原因无法编译和动态链接 GPU 支持，llamafile 将回退到 CPU 推理。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">源码安装</font></font></h2><a id="user-content-source-installation" class="anchor" aria-label="永久链接：源码安装" href="#source-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 llamafile 上进行开发需要现代版本的 GNU</font></font><code>make</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
命令（</font></font><code>gmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在某些系统上调用）</font></font><code>sha256sum</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（否则</font></font><code>cc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
将用于构建它），</font></font><code>wget</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（或</font></font><code>curl</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），并且可以在</font><a href="https://cosmo.zip/pub/cosmos/bin/" rel="nofollow"><font style="vertical-align: inherit;">https://cosmo.zip/pub/cosmos/bin/</font></a></font><code>unzip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上获取
</font><font style="vertical-align: inherit;">。 Windows 用户</font><font style="vertical-align: inherit;">也需要</font><a href="https://justine.lol/cosmo3/" rel="nofollow"><font style="vertical-align: inherit;">Cosmos bash shell。</font></a></font><a href="https://cosmo.zip/pub/cosmos/bin/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://justine.lol/cosmo3/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>make -j8
sudo make install PREFIX=/usr/local</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="make -j8
sudo make install PREFIX=/usr/local" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是如何使用 llama.cpp 命令行界面并利用 WizardCoder-Python-13B 权重为 libc 函数生成代码的示例：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>llamafile -ngl 9999 \
  -m wizardcoder-python-13b-v1.0.Q8_0.gguf \
  --temp 0 -r <span class="pl-s"><span class="pl-pds">'</span>}\n<span class="pl-pds">'</span></span> -r <span class="pl-s"><span class="pl-pds">'</span>```\n<span class="pl-pds">'</span></span> \
  -e -p <span class="pl-s"><span class="pl-pds">'</span>```c\nvoid *memcpy(void *dst, const void *src, size_t size) {\n<span class="pl-pds">'</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="llamafile -ngl 9999 \
  -m wizardcoder-python-13b-v1.0.Q8_0.gguf \
  --temp 0 -r '}\n' -r '```\n' \
  -e -p '```c\nvoid *memcpy(void *dst, const void *src, size_t size) {\n'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是一个类似的示例，它使用 Mistral-7B-Instruct 权重进行散文写作：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>llamafile -ngl 9999 \
  -m mistral-7b-instruct-v0.1.Q4_K_M.gguf \
  -p <span class="pl-s"><span class="pl-pds">'</span>[INST]Write a story about llamas[/INST]<span class="pl-pds">'</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="llamafile -ngl 9999 \
  -m mistral-7b-instruct-v0.1.Q4_K_M.gguf \
  -p '[INST]Write a story about llamas[/INST]'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下示例展示了如何将 llamafile 用作交互式聊天机器人，让您可以查询训练数据中包含的知识：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>llamafile -m llama-65b-Q5_K.gguf -p <span class="pl-s"><span class="pl-pds">'</span></span>
<span class="pl-s">The following is a conversation between a Researcher and their helpful AI assistant Digital Athena which is a large language model trained on the sum of human knowledge.</span>
<span class="pl-s">Researcher: Good morning.</span>
<span class="pl-s">Digital Athena: How can I help you today?</span>
<span class="pl-s">Researcher:<span class="pl-pds">'</span></span> --interactive --color --batch_size 1024 --ctx_size 4096 \
--keep -1 --temp 0 --mirostat 2 --in-prefix <span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> --interactive-first \
--in-suffix <span class="pl-s"><span class="pl-pds">'</span>Digital Athena:<span class="pl-pds">'</span></span> --reverse-prompt <span class="pl-s"><span class="pl-pds">'</span>Researcher:<span class="pl-pds">'</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="llamafile -m llama-65b-Q5_K.gguf -p '
The following is a conversation between a Researcher and their helpful AI assistant Digital Athena which is a large language model trained on the sum of human knowledge.
Researcher: Good morning.
Digital Athena: How can I help you today?
Researcher:' --interactive --color --batch_size 1024 --ctx_size 4096 \
--keep -1 --temp 0 --mirostat 2 --in-prefix ' ' --interactive-first \
--in-suffix 'Digital Athena:' --reverse-prompt 'Researcher:'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是如何使用 llamafile 总结 HTML URL 的示例：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>(
  <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">'</span>[INST]Summarize the following text:<span class="pl-pds">'</span></span>
  links -codepage utf-8 \
        -force-html \
        -width 500 \
        -dump https://www.poetryfoundation.org/poems/48860/the-raven <span class="pl-k">|</span>
    sed <span class="pl-s"><span class="pl-pds">'</span>s/   */ /g<span class="pl-pds">'</span></span>
  <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">'</span>[/INST]<span class="pl-pds">'</span></span>
) <span class="pl-k">|</span> llamafile -ngl 9999 \
      -m mistral-7b-instruct-v0.2.Q5_K_M.gguf \
      -f /dev/stdin \
      -c 0 \
      --temp 0 \
      -n 500 \
      --no-display-prompt <span class="pl-k">2&gt;</span>/dev/null</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="(
  echo '[INST]Summarize the following text:'
  links -codepage utf-8 \
        -force-html \
        -width 500 \
        -dump https://www.poetryfoundation.org/poems/48860/the-raven |
    sed 's/   */ /g'
  echo '[/INST]'
) | llamafile -ngl 9999 \
      -m mistral-7b-instruct-v0.2.Q5_K_M.gguf \
      -f /dev/stdin \
      -c 0 \
      --temp 0 \
      -n 500 \
      --no-display-prompt 2>/dev/null" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是如何使用 llamafile 来描述 jpg/png/gif/bmp 图像：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>llamafile -ngl 9999 --temp 0 \
  --image <span class="pl-k">~</span>/Pictures/lemurs.jpg \
  -m llava-v1.5-7b-Q4_K.gguf \
  --mmproj llava-v1.5-7b-mmproj-Q4_0.gguf \
  -e -p <span class="pl-s"><span class="pl-pds">'</span>### User: What do you see?\n### Assistant: <span class="pl-pds">'</span></span> \
  --no-display-prompt <span class="pl-k">2&gt;</span>/dev/null</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="llamafile -ngl 9999 --temp 0 \
  --image ~/Pictures/lemurs.jpg \
  -m llava-v1.5-7b-Q4_K.gguf \
  --mmproj llava-v1.5-7b-mmproj-Q4_0.gguf \
  -e -p '### User: What do you see?\n### Assistant: ' \
  --no-display-prompt 2>/dev/null" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以使用 BNF 语法来强制输出是可预测的，并且可以在 shell 脚本中安全使用。最简单的语法是
</font></font><code>--grammar 'root ::= "yes" | "no"'</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强制 LLM 仅打印到标准输出</font></font><code>"yes\n"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>"no\n"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。另一个例子是，如果您想编写一个脚本来重命名所有图像文件，您可以说：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>llamafile -ngl 9999 --temp 0 \
    --image lemurs.jpg \
    -m llava-v1.5-7b-Q4_K.gguf \
    --mmproj llava-v1.5-7b-mmproj-Q4_0.gguf \
    --grammar <span class="pl-s"><span class="pl-pds">'</span>root ::= [a-z]+ (" " [a-z]+)+<span class="pl-pds">'</span></span> \
    -e -p <span class="pl-s"><span class="pl-pds">'</span>### User: What do you see?\n### Assistant: <span class="pl-pds">'</span></span> \
    --no-display-prompt <span class="pl-k">2&gt;</span>/dev/null <span class="pl-k">|</span>
  sed -e<span class="pl-s"><span class="pl-pds">'</span>s/ /_/g<span class="pl-pds">'</span></span> -e<span class="pl-s"><span class="pl-pds">'</span>s/$/.jpg/<span class="pl-pds">'</span></span>
a_baby_monkey_on_the_back_of_a_mother.jpg</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="llamafile -ngl 9999 --temp 0 \
    --image lemurs.jpg \
    -m llava-v1.5-7b-Q4_K.gguf \
    --mmproj llava-v1.5-7b-mmproj-Q4_0.gguf \
    --grammar 'root ::= [a-z]+ (&quot; &quot; [a-z]+)+' \
    -e -p '### User: What do you see?\n### Assistant: ' \
    --no-display-prompt 2>/dev/null |
  sed -e's/ /_/g' -e's/$/.jpg/'
a_baby_monkey_on_the_back_of_a_mother.jpg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面是如何运行 llama.cpp 的内置 HTTP 服务器的示例。此示例使用 LLaVA v1.5-7B，这是一种多模式 LLM，可与 llama.cpp 最近添加的图像输入支持配合使用。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>llamafile -ngl 9999 \
  -m llava-v1.5-7b-Q8_0.gguf \
  --mmproj llava-v1.5-7b-mmproj-Q8_0.gguf \
  --host 0.0.0.0</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="llamafile -ngl 9999 \
  -m llava-v1.5-7b-Q8_0.gguf \
  --mmproj llava-v1.5-7b-mmproj-Q8_0.gguf \
  --host 0.0.0.0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上述命令将在您的个人计算机上启动浏览器选项卡以显示 Web 界面。它可以让您与您的LLM聊天并向其上传图像。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建 llama 文件</font></font></h2><a id="user-content-creating-llamafiles" class="anchor" aria-label="永久链接：创建 llamafiles" href="#creating-llamafiles"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果你想直接说：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./llava.llamafile</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./llava.llamafile" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...并让它运行 Web 服务器而无需指定参数，然后您可以嵌入权重和一个特殊的</font></font><code>.args</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内部，它指定默认参数。首先，让我们创建一个名为的文件
</font></font><code>.args</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，其中包含以下内容：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>-m
llava-v1.5-7b-Q8_0.gguf
--mmproj
llava-v1.5-7b-mmproj-Q8_0.gguf
--host
0.0.0.0
-ngl
9999
...</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="-m
llava-v1.5-7b-Q8_0.gguf
--mmproj
llava-v1.5-7b-mmproj-Q8_0.gguf
--host
0.0.0.0
-ngl
9999
..." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正如我们在上面看到的，每行有一个参数。该</font></font><code>...</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数可以选择指定用户传递的任何其他 CLI 参数的插入位置。接下来，我们将权重和参数文件添加到可执行文件中：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>cp /usr/local/bin/llamafile llava.llamafile

zipalign -j0 \
  llava.llamafile \
  llava-v1.5-7b-Q8_0.gguf \
  llava-v1.5-7b-mmproj-Q8_0.gguf \
  .args

./llava.llamafile</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cp /usr/local/bin/llamafile llava.llamafile

zipalign -j0 \
  llava.llamafile \
  llava-v1.5-7b-Q8_0.gguf \
  llava-v1.5-7b-mmproj-Q8_0.gguf \
  .args

./llava.llamafile" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">恭喜。您刚刚制作了自己的 LLM 可执行文件，可以轻松与您的朋友分享。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分配</font></font></h2><a id="user-content-distribution" class="anchor" aria-label="永久链接：分布" href="#distribution"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与朋友分享 llamafile 的一种好方法是将其发布到 Hugging Face 上。如果您这样做，那么建议您在 Hugging Face 提交消息中提及您在构建 llamafile 时使用的 llamafile 的 git 修订版或发布版本。这样，在线的每个人都可以验证其可执行内容的来源。如果您对 llama.cpp 或 cosmopolitan 源代码进行了更改，则 Apache 2.0 许可证要求您解释更改的内容。实现此目的的一种方法是在您的 llamafile 中嵌入一条通知，用于</font></font><code>zipalign</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
描述更改，并在您的 Hugging Face 提交中提及它。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行时安装的每个 llamafile 程序都有一个手册页</font></font><code>sudo make install</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。命令手册也被排版为 PDF 文件，您可以从我们的 GitHub 发布页面下载。最后，大多数命令在传递标志时都会显示该信息</font></font><code>--help</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术细节</font></font></h2><a id="user-content-technical-details" class="anchor" aria-label="永久链接：技术细节" href="#technical-details"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是我们用来创建有史以来最胖的可执行格式的技巧的简要概述。长话短说，llamafile 是一个 shell 脚本，可以自行启动并在几毫秒内对嵌入的权重进行推理，而无需复制或安装。使这成为可能的是 mmap()。 llama.cpp 可执行文件和权重都连接到 shell 脚本中。然后 shell 脚本提取一个微小的加载程序，将可执行文件映射到内存中。然后，llama.cpp 可执行文件再次将 shell 脚本作为文件打开，并再次调用 mmap() 将权重拉入内存并使 CPU 和 GPU 可以直接访问它们。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ZIP 权重嵌入</font></font></h3><a id="user-content-zip-weights-embedding" class="anchor" aria-label="永久链接：ZIP 权重嵌入" href="#zip-weights-embedding"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 llama.cpp 可执行文件中嵌入权重的技巧是确保本地文件在页面大小边界上对齐。这样，假设 zip 文件未压缩，一旦它被 mmap() 到内存中，我们就可以直接将指针传递给 Apple Metal 等 GPU，这要求数据的页面大小对齐。由于现有的 ZIP 归档工具没有对齐标志，因此我们必须编写大约</font></font><a href="/Mozilla-Ocho/llamafile/blob/main/llamafile/zipalign.c"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">500 行代码</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来自己插入 ZIP 文件。然而，一旦到达那里，每个现有的 ZIP 程序都应该能够读取它们，只要它们支持 ZIP64。如果我们为串联文件发明了自己的文件格式，这使得权重比其他方式更容易访问。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">微架构的可移植性</font></font></h3><a id="user-content-microarchitectural-portability" class="anchor" aria-label="永久链接：微架构的可移植性" href="#microarchitectural-portability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Intel 和 AMD 微处理器上，llama.cpp 大部分时间都花在 matmul Quant 上，通常为 SSSE3、AVX 和 AVX2 编写三次。 llamafile 将每个函数提取到一个单独的文件中，该文件可以</font></font><code>#include</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多次编辑，并具有不同的
</font></font><code>__attribute__((__target__("arch")))</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数属性。然后，添加一个包装函数，该函数使用 Cosmopolitan 的</font></font><code>X86_HAVE(FOO)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
功能来运行时分派到适当的实现。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">架构可移植性</font></font></h3><a id="user-content-architecture-portability" class="anchor" aria-label="永久链接：架构可移植性" href="#architecture-portability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 通过构建 llama.cpp 两次来解决架构可移植性：一次针对 AMD64，另一次针对 ARM64。然后它用带有 MZ 前缀的 shell 脚本包装它们。在 Windows 上，它将作为本机二进制文件运行。在 Linux 上，它将提取一个名为</font></font><a href="https://github.com/jart/cosmopolitan/blob/master/ape/loader.c"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">APE Loader</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的小型 8kb 可执行文件
，</font></font><code>${TMPDIR:-${HOME:-.}}/.ape</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它将 shell 脚本的二进制部分映射到内存中。通过运行编译器</font></font><a href="https://github.com/jart/cosmopolitan/blob/master/tool/build/assimilate.c"><code>assimilate</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
附带的程序</font><font style="vertical-align: inherit;">可以避免此过程
</font></font><code>cosmocc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。该
</font></font><code>assimilate</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">程序的作用是将 shell 脚本可执行文件转换为主机平台的本机可执行格式。这保证了传统发布流程在需要时存在后备路径。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPU支持</font></font></h3><a id="user-content-gpu-support-1" class="anchor" aria-label="永久链接：GPU 支持" href="#gpu-support-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cosmopolitan Libc 使用静态链接，因为这是使相同的可执行文件在六个操作系统上运行的唯一方法。这对 llama.cpp 提出了挑战，因为不可能静态链接 GPU 支持。我们解决这个问题的方法是检查主机系统上是否安装了编译器。对于 Apple，这将是 Xcode，而对于其他平台，这将是</font></font><code>nvcc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. llama.cpp 具有每个 GPU 模块的单个文件实现，名为</font></font><code>ggml-metal.m</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(Objective C) 和</font></font><code>ggml-cuda.cu</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(Nvidia C)。 llamafile 将这些源文件嵌入 zip 存档中，并要求平台编译器在运行时针对本机 GPU 微架构构建它们。如果它有效，则它与平台 C 库 dlopen() 实现链接。请参阅</font></font><a href="/Mozilla-Ocho/llamafile/blob/main/llamafile/cuda.c"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile/cuda.c</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和
</font></font><a href="/Mozilla-Ocho/llamafile/blob/main/llamafile/metal.c"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile/metal.c</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了使用特定于平台的 dlopen() 函数，我们需要要求特定于平台的编译器构建一个公开这些接口的小型可执行文件。在 ELF 平台上，Cosmopolitan Libc 将此帮助程序可执行文件与平台的 ELF 解释器一起映射到内存中。然后，平台 C 库负责链接所有 GPU 库，然后运行 &ZeroWidthSpace;&ZeroWidthSpace;longjmp() 返回到 Cosmopolitan 的帮助程序。可执行程序现在处于一种奇怪的混合状态，其中存在两个具有不同 ABI 的独立 C 库。例如，线程本地存储在每个操作系统上的工作方式不同，如果 TLS 寄存器没有指向适当的内存，程序就会崩溃。 Cosmopolitan Libc 在 AMD 上解决这个问题的方法是使用 SSE 在运行时重新编译可执行文件，将</font></font><code>%fs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寄存器访问更改为</font></font><code>%gs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
需要一毫秒的时间。在 ARM 上，Cosmo 使用</font></font><code>x28</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TLS 寄存器，可以通过</font></font><code>-ffixed-x28</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在编译 GPU 模块时传递标志来确保安全。最后，llamafile 使用该</font></font><code>__ms_abi__</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">属性，以便应用程序和 GPU 模块之间传递的函数指针符合 Windows 调用约定。令人惊讶的是，我们测试的每个编译器，包括 Linux 上的 nvcc 甚至 MacOS 上的 Objective-C，都支持编译 WIN32 风格的函数，从而确保您的 llamafile 在 Windows 上运行时能够与 Windows 驱动程序通信，而无需重新编译为 Windows 的单独文件。</font><font style="vertical-align: inherit;">
有关更多详细信息，</font><font style="vertical-align: inherit;">请参阅
</font></font><a href="https://github.com/jart/cosmopolitan/blob/master/libc/dlopen/dlopen.c"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cosmopolitan/dlopen.c 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于模型的注释</font></font></h2><a id="user-content-a-note-about-models" class="anchor" aria-label="永久链接：关于模型的注释" href="#a-note-about-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上面提供的示例 llamafiles 不应被解释为 Mozilla 对特定模型、许可证或数据集的认可或建议。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全</font></font></h2><a id="user-content-security" class="anchor" aria-label="永久链接：安全" href="#security"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">llamafile 将承诺（）和 SECCOMP 沙箱添加到 llama.cpp 中。默认情况下启用此功能。可以通过传递标志来关闭它</font></font><code>--unsecure</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
。沙盒目前仅在不带 GPU 的系统上支持 Linux 和 OpenBSD；在其他平台上，它只会记录一条警告。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的安全方法具有以下优点：</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动后，您的 HTTP 服务器根本无法访问文件系统。这很好，因为这意味着如果有人在 llama.cpp 服务器中发现错误，那么他们访问您计算机上的敏感信息或更改其配置的可能性就会大大降低。在 Linux 上，我们能够进一步沙箱化； HTTP 服务器在启动后允许使用的唯一与网络相关的系统调用是accept()。如果您的 HTTP 服务器受到威胁，这会进一步限制攻击者窃取信息的能力。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主 CLI 命令根本无法访问网络。这是由操作系统内核强制执行的。它也将无法写入文件系统。如果在 GGUF 文件格式中发现错误，攻击者可以制作恶意权重文件并将其发布到网上，这可以确保您的计算机安全。此规则的唯一例外是如果您传递标志</font></font><code>--prompt-cache</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">而没有指定</font></font><code>--prompt-cache-ro</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。在这种情况下，当前需要削弱安全性以允许</font></font><code>cpath</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问</font></font><code>wpath</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，但网络访问仍将被禁止。</font></font></p>
</li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">因此，您的 llamafile 能够保护自己免受外界侵害，但这并不意味着您可以免受 llamafile 的侵害。沙箱是自我强加的。如果您从不受信任的来源获得 llamafile，那么其作者可能只是对其进行了修改，以不这样做。在这种情况下，您可以在另一个沙箱（例如虚拟机）中运行不受信任的 llamafile，以确保它的行为符合您的预期。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可</font></font></h2><a id="user-content-licensing" class="anchor" aria-label="永久链接：许可" href="#licensing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然 llamafile 项目是 Apache 2.0 许可的，但我们对 llama.cpp 的更改是在 MIT 下许可的（就像 llama.cpp 项目本身一样），以便在将来保持兼容性和可上游性（如果需要）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本页的 llamafile 徽标是在 DALL·E 3 的帮助下生成的。</font></font></p>
<p dir="auto"><a href="https://star-history.com/#Mozilla-Ocho/llamafile&amp;Date" rel="nofollow"><img src="https://camo.githubusercontent.com/0dd36fc63c34df5480cc15de34b430cb10b5cd818196559dc28ea0c1201ee7dd/68747470733a2f2f6170692e737461722d686973746f72792e636f6d2f7376673f7265706f733d4d6f7a696c6c612d4f63686f2f6c6c616d6166696c6526747970653d44617465" alt="明星历史图" data-canonical-src="https://api.star-history.com/svg?repos=Mozilla-Ocho/llamafile&amp;type=Date" style="max-width: 100%;"></a></p>
</article></div>
