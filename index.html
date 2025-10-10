export default {
  async fetch(request, env, ctx) {
    const url = new URL(request.url);
    
    // 简单的路由
    if (url.pathname === '/') {
      return new Response(html, {
        headers: { 'content-type': 'text/html;charset=UTF-8' },
      });
    }
    
    if (url.pathname === '/api/hello') {
      return new Response(JSON.stringify({ message: 'Hello from Cloudflare Worker!' }), {
        headers: { 'content-type': 'application/json' },
      });
    }
    
    return new Response('Not Found', { status: 404 });
  },
};

const html = `
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Worker App</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 40px; }
        .container { max-width: 800px; margin: 0 auto; }
    </style>
</head>
<body>
    <div class="container">
        <h1>🚀 成功部署到 Cloudflare Worker!</h1>
        <p>这是一个通过 GitHub 一键部署的示例应用。</p>
        <button onclick="fetchData()">测试 API</button>
        <div id="result"></div>
    </div>
    <script>
        async function fetchData() {
            const response = await fetch('/api/hello');
            const data = await response.json();
            document.getElementById('result').innerHTML = 'API响应: ' + data.message;
        }
    </script>
</body>
</html>
`;