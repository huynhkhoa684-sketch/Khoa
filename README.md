[shoptech_landing_page.html](https://github.com/user-attachments/files/27697333/shoptech_landing_page.html)
# Khoa
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: var(--font-sans); color: var(--color-text-primary); }
.hero { padding: 3rem 2rem 2.5rem; text-align: center; border-bottom: 0.5px solid var(--color-border-tertiary); }
.badge { display: inline-block; background: #E6F1FB; color: #0C447C; font-size: 12px; padding: 4px 14px; border-radius: 99px; margin-bottom: 1.2rem; }
.hero h1 { font-size: 28px; font-weight: 500; line-height: 1.35; margin-bottom: 0.75rem; }
.hero h1 span { color: #185FA5; }
.hero p { font-size: 15px; color: var(--color-text-secondary); max-width: 520px; margin: 0 auto 1.5rem; line-height: 1.7; }
.hero-btns { display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; }
.btn-primary { background: #185FA5; color: #E6F1FB; border: none; padding: 9px 22px; border-radius: var(--border-radius-md); font-size: 14px; cursor: pointer; }
.btn-outline { background: transparent; color: var(--color-text-primary); border: 0.5px solid var(--color-border-secondary); padding: 9px 22px; border-radius: var(--border-radius-md); font-size: 14px; cursor: pointer; }
.info-bar { display: flex; justify-content: center; gap: 2rem; padding: 1.25rem 2rem; border-bottom: 0.5px solid var(--color-border-tertiary); flex-wrap: wrap; }
.info-item { display: flex; align-items: center; gap: 6px; font-size: 13px; color: var(--color-text-secondary); }
.info-item i { font-size: 16px; color: #185FA5; }
.section { padding: 2rem 1.5rem; }
.section-title { font-size: 18px; font-weight: 500; margin-bottom: 1.25rem; }
.feature-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 12px; }
.feature-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; }
.feature-icon { width: 36px; height: 36px; border-radius: var(--border-radius-md); background: #E6F1FB; display: flex; align-items: center; justify-content: center; margin-bottom: 0.75rem; }
.feature-icon i { font-size: 18px; color: #185FA5; }
.feature-card h3 { font-size: 14px; font-weight: 500; margin-bottom: 4px; }
.feature-card p { font-size: 13px; color: var(--color-text-secondary); line-height: 1.6; }
.tech-grid { display: flex; flex-wrap: wrap; gap: 8px; }
.tech-tag { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: 99px; padding: 5px 14px; font-size: 13px; color: var(--color-text-secondary); }
.tech-tag.highlight { background: #E6F1FB; color: #185FA5; border-color: #B5D4F4; }
.test-table { width: 100%; font-size: 13px; border-collapse: collapse; }
.test-table th { text-align: left; padding: 8px 10px; font-weight: 500; font-size: 12px; color: var(--color-text-secondary); border-bottom: 0.5px solid var(--color-border-tertiary); }
.test-table td { padding: 8px 10px; border-bottom: 0.5px solid var(--color-border-tertiary); vertical-align: middle; }
.pass { color: #3B6D11; font-size: 13px; }
.divider { height: 0.5px; background: var(--color-border-tertiary); }
.stat-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; }
.stat-card { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 1rem; text-align: center; }
.stat-num { font-size: 24px; font-weight: 500; color: #185FA5; }
.stat-label { font-size: 12px; color: var(--color-text-secondary); margin-top: 2px; }
.footer { padding: 1.5rem 2rem; text-align: center; border-top: 0.5px solid var(--color-border-tertiary); font-size: 13px; color: var(--color-text-secondary); }
.author-row { display: flex; justify-content: center; align-items: center; gap: 12px; margin-bottom: 0.5rem; }
.avatar { width: 36px; height: 36px; border-radius: 50%; background: #E6F1FB; display: flex; align-items: center; justify-content: center; font-size: 13px; font-weight: 500; color: #185FA5; }
</style>

<h2 class="sr-only">Trang giới thiệu đồ án: Website thương mại điện tử có hỗ trợ AI – ShopTech</h2>

<div class="hero">
  <div class="badge">Đồ án môn học · HK2 2024-2025</div>
  <h1>Website TMĐT<br><span>có hỗ trợ trí tuệ nhân tạo</span></h1>
  <p>ShopTech – nền tảng thương mại điện tử tích hợp Chatbot AI, hệ thống gợi ý sản phẩm và Agentic AI tự động hoá quản trị.</p>
  <div class="hero-btns">
    <button class="btn-primary" onclick="sendPrompt('Giới thiệu chi tiết về kiến trúc hệ thống ShopTech')">Xem kiến trúc hệ thống ↗</button>
    <button class="btn-outline" onclick="sendPrompt('Giải thích cách tích hợp Claude API vào chatbot của ShopTech')">Tích hợp Claude API ↗</button>
  </div>
</div>

<div class="info-bar">
  <div class="info-item"><i class="ti ti-user" aria-hidden="true"></i> Huỳnh Trần Đăng Khoa – 2513713</div>
  <div class="info-item"><i class="ti ti-school" aria-hidden="true"></i> Lớp CTK9C</div>
  <div class="info-item"><i class="ti ti-books" aria-hidden="true"></i> GVHD: Phan Thị Thanh Nga</div>
</div>

<div class="section">
  <div class="stat-grid">
    <div class="stat-card"><div class="stat-num">8/8</div><div class="stat-label">Test case đạt</div></div>
    <div class="stat-card"><div class="stat-num">~2s</div><div class="stat-label">Phản hồi chatbot</div></div>
    <div class="stat-card"><div class="stat-num">3</div><div class="stat-label">Module AI</div></div>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <div class="section-title">Tính năng chính</div>
  <div class="feature-grid">
    <div class="feature-card">
      <div class="feature-icon"><i class="ti ti-robot" aria-hidden="true"></i></div>
      <h3>Chatbot AI</h3>
      <p>Tư vấn sản phẩm, hỗ trợ 24/7 qua Claude API (Anthropic)</p>
    </div>
    <div class="feature-card">
      <div class="feature-icon"><i class="ti ti-sparkles" aria-hidden="true"></i></div>
      <h3>Gợi ý sản phẩm</h3>
      <p>Content-based Filtering theo hành vi và lịch sử mua hàng</p>
    </div>
    <div class="feature-card">
      <div class="feature-icon"><i class="ti ti-settings-automation" aria-hidden="true"></i></div>
      <h3>Agentic AI</h3>
      <p>Tự động cập nhật đơn hàng, cảnh báo tồn kho, báo cáo doanh thu</p>
    </div>
    <div class="feature-card">
      <div class="feature-icon"><i class="ti ti-shield-lock" aria-hidden="true"></i></div>
      <h3>Bảo mật</h3>
      <p>bcrypt, Prepared Statements, HTTPS, chống SQL Injection & XSS</p>
    </div>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <div class="section-title">Công nghệ sử dụng</div>
  <div class="tech-grid">
    <span class="tech-tag highlight">Claude API (Anthropic)</span>
    <span class="tech-tag highlight">PHP</span>
    <span class="tech-tag highlight">MySQL</span>
    <span class="tech-tag">Bootstrap 5</span>
    <span class="tech-tag">HTML / CSS / JS</span>
    <span class="tech-tag">bcrypt</span>
    <span class="tech-tag">Three-tier Architecture</span>
    <span class="tech-tag">Content-based Filtering</span>
    <span class="tech-tag">OWASP Security</span>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <div class="section-title">Kết quả kiểm thử</div>
  <table class="test-table">
    <tr><th>#</th><th>Chức năng</th><th>Kết quả</th></tr>
    <tr><td>1</td><td>Đăng ký / Đăng nhập</td><td class="pass">✓ Đạt</td></tr>
    <tr><td>2</td><td>Thêm giỏ hàng & Đặt hàng</td><td class="pass">✓ Đạt</td></tr>
    <tr><td>3</td><td>Chatbot AI phản hồi (~2s)</td><td class="pass">✓ Đạt</td></tr>
    <tr><td>4</td><td>Gợi ý sản phẩm (4 SP)</td><td class="pass">✓ Đạt</td></tr>
    <tr><td>5</td><td>Agentic AI – email tồn kho</td><td class="pass">✓ Đạt</td></tr>
    <tr><td>6</td><td>Admin quản lý sản phẩm</td><td class="pass">✓ Đạt</td></tr>
  </table>
</div>

<div class="divider"></div>

<div class="footer">
  <div class="author-row">
    <div class="avatar">HK</div>
    <div style="text-align:left;">
      <div style="font-weight:500; color: var(--color-text-primary);">Huỳnh Trần Đăng Khoa</div>
      <div>Trường ĐH Đà Lạt · Khoa CNTT · 2024-2025</div>
    </div>
  </div>
  <div>Đề tài: Website TMĐT có hỗ trợ Trí tuệ Nhân tạo (AI)</div>
</div>
