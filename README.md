<div data-target="readme-toc.content" class="Box-body px-5 pb-5">
            <article class="markdown-body entry-content container-lg" itemprop="text"><h1 dir="auto"><a id="user-content-binance-trader-master" class="anchor" aria-hidden="true" href="#binance-trader-master"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>binance-trader-master</h1>
<p dir="auto">This is an experimental bot for auto trading the binance.com exchange. <a href="https://twitter.com/yasinkuyu" rel="nofollow">@binance-trader-master
</a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/yasinkuyu/binance-trader/blob/master/img/screenshot.png"><img src="https://imgs.search.brave.com/Fb-g_uueYouR8cymE0IZn38sGwdOnTdOWbEkA5uTVTY/rs:fit:460:215:1/g:ce/aHR0cHM6Ly9jZG4u/YWthbWFpLnN0ZWFt/c3RhdGljLmNvbS9z/dGVhbS9hcHBzLzg0/ODMxMC9oZWFkZXIu/anBnP3Q9MTYwMTEx/MDAzOA" alt="Screenshot" style="max-width: 100%;"></a></p>
<h2 dir="auto"><a id="user-content-configuration" class="anchor" aria-hidden="true" href="#configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Configuration</h2>
<ol dir="auto">
<li>
<p dir="auto"><a href="https://www.binance.com/?ref=10701111" rel="nofollow">Signup</a> for Binance</p>
</li>
<li>
<p dir="auto">Enable Two-factor Authentication</p>
</li>
<li>
<p dir="auto">Go API Center, <a href="https://www.binance.com/en/my/settings/api-management?ref=10701111" rel="nofollow">Create New</a> Api Key</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code> [✓] Read Info [✓] Enable Trading [X] Enable Withdrawals
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" [✓] Read Info [✓] Enable Trading [X] Enable Withdrawals" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto">Rename <strong>config.sample.py</strong> to <code>config.py</code> / <strong>orders.sample.db</strong> to <code>orders.db</code></p>
</li>
<li>
<p dir="auto">Get an API and Secret Key, insert into <code>config.py</code></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code> API key for account access
 api_key = ''
 Secret key for account access
 api_secret = ''

 [API Docs](https://www.binance.com/restapipub.html)
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" API key for account access
 api_key = ''
 Secret key for account access
 api_secret = ''

 [API Docs](https://www.binance.com/restapipub.html)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto">Optional: Modify recv_window value (not recommended)</p>
</li>
<li>
<p dir="auto">Optional: run as an excutable application in Docker containers</p>
</li>
</ol>
<h2 dir="auto"><a id="user-content-support" class="anchor" aria-hidden="true" href="#support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Support</h2>
<p dir="auto"><a href="https://www.binance.com/?ref=10701111" rel="nofollow">https://www.binance.com/?ref=10701111</a></p>
<h2 dir="auto"><a id="user-content-features" class="anchor" aria-hidden="true" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Features</h2>
<ul dir="auto">
<li>Implementation of all General, Market Data and Account endpoints.</li>
<li>Asyncio implementation</li>
<li>Testnet support for Spot, Futures and Vanilla Options</li>
<li>Simple handling of authentication</li>
<li>No need to generate timestamps yourself, the wrapper does it for you</li>
<li>Response exception handling</li>
<li>Websocket handling with reconnection and multiplexed connections</li>
<li>Symbol Depth Cache</li>
<li>Symbol Depth Cache</li><li>Historical Kline/Candle fetching function</li>
<li>Withdraw functionality</li>
<li>Deposit addresses</li>
<li>Margin Trading</li>
<li>Futures Trading</li>
<li>Vanilla Options</li>
<li>Support other domains (.us, .jp, etc)</li>
</ul>

<h2 dir="auto"><a id="user-content-upgrading-to-v100" class="anchor" aria-hidden="true" href="#upgrading-to-v100"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Upgrading to v1.0.0+</h2>

<p dir="auto">The breaking changes include the migration from wapi to sapi endpoints which related to the
wallet endpoints detailed in the <a href="https://binance-docs.github.io/apidocs/spot/en/#wallet-endpoints" rel="nofollow">Binance Docs</a></p>
<p dir="auto">The breaking changes include the migration from wapi to sapi endpoints which related to the
wallet endpoints detailed in the <a href="https://binance-docs.github.io/apidocs/spot/en/#wallet-endpoints" rel="nofollow">Binance Docs</a></p>
<p dir="auto">The other breaking change is for websocket streams and the Depth Cache Manager which have been
converted to use Asynchronous Context Managers. See examples in the Async section below or view the
<a href="https://python-binance.readthedocs.io/en/latest/websockets.html" rel="nofollow">websockets</a> and
<a href="https://python-binance.readthedocs.io/en/latest/depth_cache.html" rel="nofollow">depth cache</a> docs.</p>
<h2 dir="auto"><a id="user-content-quick-start" class="anchor" aria-hidden="true" href="#quick-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Quick Start</h2>
<a href="https://accounts.binance.com/en/register?ref=10099792" rel="nofollow">Register an account with Binance</a>
<p dir="auto"><a href="https://www.binance.com/en/my/settings/api-management" rel="nofollow">Generate an API Key</a> and assign relevant permissions.</p>
<p dir="auto"><a href="https://accounts.binance.com/en/register?ref=10099792" rel="nofollow">Register an account with Binance</a>.</p>
<p dir="auto"><a href="https://www.binance.com/en/my/settings/api-management" rel="nofollow">Generate an API Key</a> and assign relevant permissions.</p>
<p dir="auto">If you are using an exchange from the US, Japan or other TLD then make sure pass tld='us' when creating the
client.</p>
<p dir="auto">To use the <a href="https://testnet.binance.vision/" rel="nofollow">Spot</a> or <a href="https://testnet.binanceops.com/" rel="nofollow">Vanilla Options</a> Testnet,
pass testnet=True when creating the client.</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install python-binance</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install python-binance" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
  <div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">binance</span> <span class="pl-k">import</span> <span class="pl-v">Client</span>, <span class="pl-v">ThreadedWebsocketManager</span>, <span class="pl-v">ThreadedDepthCacheManager</span>
<span class="pl-s1">client</span> <span class="pl-c1">=</span> <span class="pl-v">Client</span>(<span class="pl-s1">api_key</span>, <span class="pl-s1">api_secret</span>)

<span class="pl-c"># get market depth</span>
<span class="pl-s1">depth</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_order_book</span>(<span class="pl-s1">symbol</span><span class="pl-c1">=</span><span class="pl-s">'BNBBTC'</span>)

<span class="pl-c"># place a test market buy order, to place an actual order use the create_order function</span>
<span class="pl-s1">order</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">create_test_order</span>(
    <span class="pl-s1">symbol</span><span class="pl-c1">=</span><span class="pl-s">'BNBBTC'</span>,
    <span class="pl-s1">side</span><span class="pl-c1">=</span><span class="pl-v">Client</span>.<span class="pl-v">SIDE_BUY</span>,
    <span class="pl-s1">type</span><span class="pl-c1">=</span><span class="pl-v">Client</span>.<span class="pl-v">ORDER_TYPE_MARKET</span>,
    <span class="pl-s1">quantity</span><span class="pl-c1">=</span><span class="pl-c1">100</span>)

<span class="pl-c"># get all symbol prices</span>
<span class="pl-s1">prices</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_all_tickers</span>()

<span class="pl-c"># withdraw 100 ETH</span>
<span class="pl-c"># check docs for assumptions around withdrawals</span>
<span class="pl-k">from</span> <span class="pl-s1">binance</span>.<span class="pl-s1">exceptions</span> <span class="pl-k">import</span> <span class="pl-v">BinanceAPIException</span>
<span class="pl-k">try</span>:
    <span class="pl-s1">result</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">withdraw</span>(
        <span class="pl-s1">asset</span><span class="pl-c1">=</span><span class="pl-s">'ETH'</span>,
        <span class="pl-s1">address</span><span class="pl-c1">=</span><span class="pl-s">'&lt;eth_address&gt;'</span>,
        <span class="pl-s1">amount</span><span class="pl-c1">=</span><span class="pl-c1">100</span>)
<span class="pl-k">except</span> <span class="pl-v">BinanceAPIException</span> <span class="pl-k">as</span> <span class="pl-s1">e</span>:
    <span class="pl-en">print</span>(<span class="pl-s1">e</span>)
<span class="pl-k">else</span>:
    <span class="pl-en">print</span>(<span class="pl-s">"Success"</span>)

<span class="pl-c"># fetch list of withdrawals</span>
<span class="pl-s1">withdraws</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_withdraw_history</span>()

<span class="pl-c"># fetch list of ETH withdrawals</span>
<span class="pl-s1">eth_withdraws</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_withdraw_history</span>(<span class="pl-s1">coin</span><span class="pl-c1">=</span><span class="pl-s">'ETH'</span>)

<span class="pl-c"># get a deposit address for BTC</span>
<span class="pl-s1">address</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_deposit_address</span>(<span class="pl-s1">coin</span><span class="pl-c1">=</span><span class="pl-s">'BTC'</span>)

<span class="pl-c"># get historical kline data from any date range</span>

<span class="pl-c"># fetch 1 minute klines for the last day up until now</span>
<span class="pl-s1">klines</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_historical_klines</span>(<span class="pl-s">"BNBBTC"</span>, <span class="pl-v">Client</span>.<span class="pl-v">KLINE_INTERVAL_1MINUTE</span>, <span class="pl-s">"1 day ago UTC"</span>)

<span class="pl-c"># fetch 30 minute klines for the last month of 2017</span>
<span class="pl-s1">klines</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_historical_klines</span>(<span class="pl-s">"ETHBTC"</span>, <span class="pl-v">Client</span>.<span class="pl-v">KLINE_INTERVAL_30MINUTE</span>, <span class="pl-s">"1 Dec, 2017"</span>, <span class="pl-s">"1 Jan, 2018"</span>)

<span class="pl-c"># fetch weekly klines since it listed</span>
<span class="pl-s1">klines</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_historical_klines</span>(<span class="pl-s">"NEOBTC"</span>, <span class="pl-v">Client</span>.<span class="pl-v">KLINE_INTERVAL_1WEEK</span>, <span class="pl-s">"1 Jan, 2017"</span>)

<span class="pl-c"># socket manager using threads</span>
<span class="pl-s1">twm</span> <span class="pl-c1">=</span> <span class="pl-v">ThreadedWebsocketManager</span>()
<span class="pl-s1">twm</span>.<span class="pl-en">start</span>()

<span class="pl-c"># depth cache manager using threads</span>
<span class="pl-s1">dcm</span> <span class="pl-c1">=</span> <span class="pl-v">ThreadedDepthCacheManager</span>()
<span class="pl-s1">dcm</span>.<span class="pl-en">start</span>()

<span class="pl-k">def</span> <span class="pl-en">handle_socket_message</span>(<span class="pl-s1">msg</span>):
    <span class="pl-en">print</span>(<span class="pl-s">f"message type: <span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">msg</span>[<span class="pl-s">'e'</span>]<span class="pl-kos">}</span></span>"</span>)
    <span class="pl-en">print</span>(<span class="pl-s1">msg</span>)

<span class="pl-k">def</span> <span class="pl-en">handle_dcm_message</span>(<span class="pl-s1">depth_cache</span>):
    <span class="pl-en">print</span>(<span class="pl-s">f"symbol <span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">depth_cache</span>.<span class="pl-s1">symbol</span><span class="pl-kos">}</span></span>"</span>)
    <span class="pl-en">print</span>(<span class="pl-s">"top 5 bids"</span>)
    <span class="pl-en">print</span>(<span class="pl-s1">depth_cache</span>.<span class="pl-en">get_bids</span>()[:<span class="pl-c1">5</span>])
    <span class="pl-en">print</span>(<span class="pl-s">"top 5 asks"</span>)
    <span class="pl-en">print</span>(<span class="pl-s1">depth_cache</span>.<span class="pl-en">get_asks</span>()[:<span class="pl-c1">5</span>])
    <span class="pl-en">print</span>(<span class="pl-s">"last update time {}"</span>.<span class="pl-en">format</span>(<span class="pl-s1">depth_cache</span>.<span class="pl-s1">update_time</span>))

<span class="pl-s1">twm</span>.<span class="pl-en">start_kline_socket</span>(<span class="pl-s1">callback</span><span class="pl-c1">=</span><span class="pl-s1">handle_socket_message</span>, <span class="pl-s1">symbol</span><span class="pl-c1">=</span><span class="pl-s">'BNBBTC'</span>)

<span class="pl-s1">dcm</span>.<span class="pl-en">start_depth_cache</span>(<span class="pl-s1">callback</span><span class="pl-c1">=</span><span class="pl-s1">handle_dcm_message</span>, <span class="pl-s1">symbol</span><span class="pl-c1">=</span><span class="pl-s">'ETHBTC'</span>)

<span class="pl-c"># replace with a current options symbol</span>
<span class="pl-s1">options_symbol</span> <span class="pl-c1">=</span> <span class="pl-s">'BTC-210430-36000-C'</span>
<span class="pl-s1">dcm</span>.<span class="pl-en">start_options_depth_cache</span>(<span class="pl-s1">callback</span><span class="pl-c1">=</span><span class="pl-s1">handle_dcm_message</span>, <span class="pl-s1">symbol</span><span class="pl-c1">=</span><span class="pl-s1">options_symbol</span>)

<span class="pl-c"># join the threaded managers to the main thread</span>
<span class="pl-s1">twm</span>.<span class="pl-en">join</span>()
<span class="pl-s1">dcm</span>.<span class="pl-en">join</span>()</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from binance import Client, ThreadedWebsocketManager, ThreadedDepthCacheManager
client = Client(api_key, api_secret)

# get market depth
depth = client.get_order_book(symbol='BNBBTC')

# place a test market buy order, to place an actual order use the create_order function
order = client.create_test_order(
    symbol='BNBBTC',
    side=Client.SIDE_BUY,
    type=Client.ORDER_TYPE_MARKET,
    quantity=100)

# get all symbol prices
prices = client.get_all_tickers()

# withdraw 100 ETH
# check docs for assumptions around withdrawals
from binance.exceptions import BinanceAPIException
try:
    result = client.withdraw(
        asset='ETH',
        address='<eth_address>',
        amount=100)
except BinanceAPIException as e:
    print(e)
else:
    print(&quot;Success&quot;)

# fetch list of withdrawals
withdraws = client.get_withdraw_history()

# fetch list of ETH withdrawals
eth_withdraws = client.get_withdraw_history(coin='ETH')

# get a deposit address for BTC
address = client.get_deposit_address(coin='BTC')

# get historical kline data from any date range

# fetch 1 minute klines for the last day up until now
klines = client.get_historical_klines(&quot;BNBBTC&quot;, Client.KLINE_INTERVAL_1MINUTE, &quot;1 day ago UTC&quot;)

# fetch 30 minute klines for the last month of 2017
klines = client.get_historical_klines(&quot;ETHBTC&quot;, Client.KLINE_INTERVAL_30MINUTE, &quot;1 Dec, 2017&quot;, &quot;1 Jan, 2018&quot;)

# fetch weekly klines since it listed
klines = client.get_historical_klines(&quot;NEOBTC&quot;, Client.KLINE_INTERVAL_1WEEK, &quot;1 Jan, 2017&quot;)

# socket manager using threads
twm = ThreadedWebsocketManager()
twm.start()

# depth cache manager using threads
dcm = ThreadedDepthCacheManager()
dcm.start()

def handle_socket_message(msg):
    print(f&quot;message type: {msg['e']}&quot;)
    print(msg)

def handle_dcm_message(depth_cache):
    print(f&quot;symbol {depth_cache.symbol}&quot;)
    print(&quot;top 5 bids&quot;)
    print(depth_cache.get_bids()[:5])
    print(&quot;top 5 asks&quot;)
    print(depth_cache.get_asks()[:5])
    print(&quot;last update time {}&quot;.format(depth_cache.update_time))

twm.start_kline_socket(callback=handle_socket_message, symbol='BNBBTC')

dcm.start_depth_cache(callback=handle_dcm_message, symbol='ETHBTC')

# replace with a current options symbol
options_symbol = 'BTC-210430-36000-C'
dcm.start_options_depth_cache(callback=handle_dcm_message, symbol=options_symbol)

# join the threaded managers to the main thread
twm.join()
dcm.join()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
  <h2 dir="auto"><a id="user-content-async-example" class="anchor" aria-hidden="true" href="#async-example"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Async Example</h2>
  <p dir="auto">Read <a href="https://sammchardy.github.io/binance/2021/05/01/async-binance-basics.html" rel="nofollow">Async basics for Binance</a>
for more information.</p>
<pre><span class="pl-k">import</span> <span class="pl-s1">asyncio</span>
<span class="pl-k">import</span> <span class="pl-s1">json</span>

<span class="pl-k">from</span> <span class="pl-s1">binance</span> <span class="pl-k">import</span> <span class="pl-v">AsyncClient</span>, <span class="pl-v">DepthCacheManager</span>, <span class="pl-v">BinanceSocketManager</span>

<span class="pl-k">async</span> <span class="pl-k">def</span> <span class="pl-en">main</span>():

    <span class="pl-c"># initialise the client</span>
    <span class="pl-s1">client</span> <span class="pl-c1">=</span> <span class="pl-k">await</span> <span class="pl-v">AsyncClient</span>.<span class="pl-en">create</span>()

    <span class="pl-c"># run some simple requests</span>
    <span class="pl-en">print</span>(<span class="pl-s1">json</span>.<span class="pl-en">dumps</span>(<span class="pl-k">await</span> <span class="pl-s1">client</span>.<span class="pl-en">get_exchange_info</span>(), <span class="pl-s1">indent</span><span class="pl-c1">=</span><span class="pl-c1">2</span>))

    <span class="pl-en">print</span>(<span class="pl-s1">json</span>.<span class="pl-en">dumps</span>(<span class="pl-k">await</span> <span class="pl-s1">client</span>.<span class="pl-en">get_symbol_ticker</span>(<span class="pl-s1">symbol</span><span class="pl-c1">=</span><span class="pl-s">"BTCUSDT"</span>), <span class="pl-s1">indent</span><span class="pl-c1">=</span><span class="pl-c1">2</span>))

    <span class="pl-c"># initialise websocket factory manager</span>
    <span class="pl-s1">bsm</span> <span class="pl-c1">=</span> <span class="pl-v">BinanceSocketManager</span>(<span class="pl-s1">client</span>)

    <span class="pl-c"># create listener using async with</span>
    <span class="pl-c"># this will exit and close the connection after 5 messages</span>
    <span class="pl-k">async</span> <span class="pl-k">with</span> <span class="pl-s1">bsm</span>.<span class="pl-en">trade_socket</span>(<span class="pl-s">'ETHBTC'</span>) <span class="pl-k">as</span> <span class="pl-s1">ts</span>:
        <span class="pl-k">for</span> <span class="pl-s1">_</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-c1">5</span>):
            <span class="pl-s1">res</span> <span class="pl-c1">=</span> <span class="pl-k">await</span> <span class="pl-s1">ts</span>.<span class="pl-en">recv</span>()
            <span class="pl-en">print</span>(<span class="pl-s">f'recv <span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">res</span><span class="pl-kos">}</span></span>'</span>)

    <span class="pl-c"># get historical kline data from any date range</span>

    <span class="pl-c"># fetch 1 minute klines for the last day up until now</span>
    <span class="pl-s1">klines</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_historical_klines</span>(<span class="pl-s">"BNBBTC"</span>, <span class="pl-v">AsyncClient</span>.<span class="pl-v">KLINE_INTERVAL_1MINUTE</span>, <span class="pl-s">"1 day ago UTC"</span>)

    <span class="pl-c"># use generator to fetch 1 minute klines for the last day up until now</span>
    <span class="pl-k">async</span> <span class="pl-k">for</span> <span class="pl-s1">kline</span> <span class="pl-c1">in</span> <span class="pl-k">await</span> <span class="pl-s1">client</span>.<span class="pl-en">get_historical_klines_generator</span>(<span class="pl-s">"BNBBTC"</span>, <span class="pl-v">AsyncClient</span>.<span class="pl-v">KLINE_INTERVAL_1MINUTE</span>, <span class="pl-s">"1 day ago UTC"</span>):
        <span class="pl-en">print</span>(<span class="pl-s1">kline</span>)

    <span class="pl-c"># fetch 30 minute klines for the last month of 2017</span>
    <span class="pl-s1">klines</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_historical_klines</span>(<span class="pl-s">"ETHBTC"</span>, <span class="pl-v">Client</span>.<span class="pl-v">KLINE_INTERVAL_30MINUTE</span>, <span class="pl-s">"1 Dec, 2017"</span>, <span class="pl-s">"1 Jan, 2018"</span>)

    <span class="pl-c"># fetch weekly klines since it listed</span>
    <span class="pl-s1">klines</span> <span class="pl-c1">=</span> <span class="pl-s1">client</span>.<span class="pl-en">get_historical_klines</span>(<span class="pl-s">"NEOBTC"</span>, <span class="pl-v">Client</span>.<span class="pl-v">KLINE_INTERVAL_1WEEK</span>, <span class="pl-s">"1 Jan, 2017"</span>)

    <span class="pl-c"># setup an async context the Depth Cache and exit after 5 messages</span>
    <span class="pl-k">async</span> <span class="pl-k">with</span> <span class="pl-v">DepthCacheManager</span>(<span class="pl-s1">client</span>, <span class="pl-s1">symbol</span><span class="pl-c1">=</span><span class="pl-s">'ETHBTC'</span>) <span class="pl-k">as</span> <span class="pl-s1">dcm_socket</span>:
        <span class="pl-k">for</span> <span class="pl-s1">_</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-c1">5</span>):
            <span class="pl-s1">depth_cache</span> <span class="pl-c1">=</span> <span class="pl-k">await</span> <span class="pl-s1">dcm_socket</span>.<span class="pl-en">recv</span>()
            <span class="pl-en">print</span>(<span class="pl-s">f"symbol <span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">depth_cache</span>.<span class="pl-s1">symbol</span><span class="pl-kos">}</span></span> updated:<span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">depth_cache</span>.<span class="pl-s1">update_time</span><span class="pl-kos">}</span></span>"</span>)
            <span class="pl-en">print</span>(<span class="pl-s">"Top 5 asks:"</span>)
            <span class="pl-en">print</span>(<span class="pl-s1">depth_cache</span>.<span class="pl-en">get_asks</span>()[:<span class="pl-c1">5</span>])
            <span class="pl-en">print</span>(<span class="pl-s">"Top 5 bids:"</span>)
            <span class="pl-en">print</span>(<span class="pl-s1">depth_cache</span>.<span class="pl-en">get_bids</span>()[:<span class="pl-c1">5</span>])

    <span class="pl-c"># Vanilla options Depth Cache works the same, update the symbol to a current one</span>
    <span class="pl-s1">options_symbol</span> <span class="pl-c1">=</span> <span class="pl-s">'BTC-210430-36000-C'</span>
    <span class="pl-k">async</span> <span class="pl-k">with</span> <span class="pl-v">OptionsDepthCacheManager</span>(<span class="pl-s1">client</span>, <span class="pl-s1">symbol</span><span class="pl-c1">=</span><span class="pl-s1">options_symbol</span>) <span class="pl-k">as</span> <span class="pl-s1">dcm_socket</span>:
        <span class="pl-k">for</span> <span class="pl-s1">_</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-c1">5</span>):
            <span class="pl-s1">depth_cache</span> <span class="pl-c1">=</span> <span class="pl-k">await</span> <span class="pl-s1">dcm_socket</span>.<span class="pl-en">recv</span>()
            <span class="pl-s1">count</span> <span class="pl-c1">+=</span> <span class="pl-c1">1</span>
            <span class="pl-en">print</span>(<span class="pl-s">f"symbol <span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">depth_cache</span>.<span class="pl-s1">symbol</span><span class="pl-kos">}</span></span> updated:<span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">depth_cache</span>.<span class="pl-s1">update_time</span><span class="pl-kos">}</span></span>"</span>)
            <span class="pl-en">print</span>(<span class="pl-s">"Top 5 asks:"</span>)
            <span class="pl-en">print</span>(<span class="pl-s1">depth_cache</span>.<span class="pl-en">get_asks</span>()[:<span class="pl-c1">5</span>])
            <span class="pl-en">print</span>(<span class="pl-s">"Top 5 bids:"</span>)
            <span class="pl-en">print</span>(<span class="pl-s1">depth_cache</span>.<span class="pl-en">get_bids</span>()[:<span class="pl-c1">5</span>])

    <span class="pl-k">await</span> <span class="pl-s1">client</span>.<span class="pl-en">close_connection</span>()

<span class="pl-k">if</span> <span class="pl-s1">__name__</span> <span class="pl-c1">==</span> <span class="pl-s">"__main__"</span>:

    <span class="pl-s1">loop</span> <span class="pl-c1">=</span> <span class="pl-s1">asyncio</span>.<span class="pl-en">get_event_loop</span>()
    <span class="pl-s1">loop</span>.<span class="pl-en">run_until_complete</span>(<span class="pl-en">main</span>())</pre>
	<h2 dir="auto"><a id="user-content-other-exchanges" class="anchor" aria-hidden="true" href="#other-exchanges"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Other Exchanges</h2>
	<p dir="auto">If you use <a href="https://testnet.binance.org/" rel="nofollow">Binance Chain</a> check out my <a href="https://github.com/sammchardy/python-binance-chain">python-binance-chain</a> library.</p>
	<p dir="auto">If you use <a href="https://www.kucoin.com/?rcode=E42cWB" rel="nofollow">Kucoin</a> check out my <a href="https://github.com/sammchardy/python-kucoin">python-kucoin</a> library.</p>
	<p dir="auto">If you use <a href="https://idex.market" rel="nofollow">IDEX</a> check out my <a href="https://github.com/sammchardy/python-idex">python-idex</a> library.</p>
	</article>
          </div>
