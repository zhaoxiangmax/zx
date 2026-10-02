---
# A Blank widget showcasing social media & video channels.
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

title: 社交与视频
subtitle: 关注我的观鸟、旅行与自然保护视频

design:
  columns: '1'
---

<style>
.social-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1.1rem;max-width:760px;margin:1.5rem auto 0;}
.social-card{display:flex;align-items:center;gap:1rem;padding:1rem 1.2rem;border-radius:14px;background:rgba(127,127,127,.06);border:1px solid rgba(127,127,127,.15);text-decoration:none;color:inherit;transition:transform .15s ease,box-shadow .15s ease;}
.social-card:hover{transform:translateY(-3px);box-shadow:0 8px 20px rgba(0,0,0,.14);text-decoration:none;}
.social-ico{flex:0 0 48px;width:48px;height:48px;border-radius:12px;display:flex;align-items:center;justify-content:center;color:#fff;font-size:1.5rem;background:var(--brand,#444);}
.social-ico svg{width:26px;height:26px;fill:#fff;}
.social-meta{display:flex;flex-direction:column;line-height:1.3;min-width:0;}
.social-name{font-weight:700;font-size:1.05rem;}
.social-handle{font-size:.85rem;opacity:.65;overflow:hidden;text-overflow:ellipsis;}
.video-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1.1rem;max-width:960px;margin:1.5rem auto 0;}
.video-wrap{position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:12px;box-shadow:0 2px 12px rgba(0,0,0,.12);}
.video-wrap iframe{position:absolute;top:0;left:0;width:100%;height:100%;border:0;}
.social-sub{text-align:center;font-weight:700;font-size:1.15rem;margin:2.5rem 0 0;}
</style>

<div class="video-grid">
  <div class="video-wrap"><iframe src="https://www.youtube-nocookie.com/embed/9U-ozrqZJuo" title="A road trip summer from Perth, WA, Australia" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen loading="lazy"></iframe></div>
  <div class="video-wrap"><iframe src="https://www.youtube-nocookie.com/embed/6DOUL5LtAA8" title="Xiang's Lunar New Year" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen loading="lazy"></iframe></div>
  <div class="video-wrap"><iframe src="https://www.youtube-nocookie.com/embed/XHLogmNmm-U" title="A summer in Panda's habitat in Southwest China" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen loading="lazy"></iframe></div>
</div>

<p class="social-sub">在这些平台找到我</p>

<div class="social-grid">

  <a class="social-card" href="https://www.youtube.com/@zhaoxiang3998/videos" target="_blank" rel="noopener">
    <span class="social-ico" style="--brand:#FF0000;"><i class="fab fa-youtube"></i></span>
    <span class="social-meta"><span class="social-name">YouTube</span><span class="social-handle">@zhaoxiang3998</span></span>
  </a>

  <a class="social-card" href="https://www.tiktok.com/@maxwell2159" target="_blank" rel="noopener">
    <span class="social-ico" style="--brand:#000000;"><i class="fab fa-tiktok"></i></span>
    <span class="social-meta"><span class="social-name">TikTok</span><span class="social-handle">@maxwell2159</span></span>
  </a>

  <a class="social-card" href="https://www.douyin.com/user/MS4wLjABAAAA7KMyyh24FjVqaa9CMaxuBlmf8kOyeloW-NlEdMm1c30RIRmecYJxQ02iOq8oeUgf" target="_blank" rel="noopener">
    <span class="social-ico" style="--brand:#161823;"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12.53.02C13.84 0 15.14.01 16.44 0c.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"/></svg></span>
    <span class="social-meta"><span class="social-name">抖音</span><span class="social-handle">在抖音观看</span></span>
  </a>

  <a class="social-card" href="https://www.xiaohongshu.com/user/profile/574160ad50c4b43f284f91dc" target="_blank" rel="noopener">
    <span class="social-ico" style="--brand:#FF2442;"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/></svg></span>
    <span class="social-meta"><span class="social-name">小红书</span><span class="social-handle">查看主页</span></span>
  </a>

</div>
