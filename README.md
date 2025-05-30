<h1>📂 Copy-Drive</h1>

<p><strong>Copy-Drive</strong> là một công cụ chạy trên <a href="https://colab.research.google.com/" target="_blank">Google Colab</a>, cho phép sao chép thư mục Google Drive cá nhân hoặc được chia sẻ từ thư mục này sang thư mục khác.</p>

<h2>🎯 Tính năng</h2>
<ul>
  <li>Sao chép toàn bộ thư mục bao gồm cả thư mục con.</li>
  <li>Hỗ trợ Google Drive cá nhân và Shared Drives.</li>
  <li>Cho phép đặt giới hạn tổng dung lượng sao chép.</li>
  <li>Bỏ qua các file/thư mục có chứa từ khóa nhất định.</li>
</ul>

<h2>⚙️ Cài đặt</h2>
<p>Dành cho môi trường Google Colab. Không cần cài đặt cục bộ.</p>
<p>Tuy nhiên, nếu muốn chạy cục bộ (ít phổ biến), bạn cần cài các thư viện sau:</p>


<pre><code>git clone https://d4m-dev/Copy-Drive.git && cd Copy-Drive && ls</code></pre>

<pre><code>pip install -r requirements.txt</code></pre>

<h2>🧠 Hướng dẫn sử dụng</h2>
<ol>
  <li>Truy cập Google Colab: <a href="https://colab.research.google.com/" target="_blank">https://colab.research.google.com/</a></li>
  <li>Dán mã Python từ file <code>run.py</code> và <code>input.py</code> vào.</li>
  <li>Chạy các ô nhập liệu để nhập:
    <ul>
      <li>Link thư mục nguồn (Google Drive shared hoặc cá nhân).</li>
      <li>Link thư mục đích.</li>
      <li>Trang bắt đầu và trang kết thúc để lọc số lượng file.</li>
      <li>Dung lượng tối đa cho phép (đơn vị: GB).</li>
      <li>Các từ khóa để loại trừ file hoặc thư mục.</li>
    </ul>
  </li>
  <li>Chạy ô thực thi để bắt đầu quá trình sao chép.</li>
</ol>

<h2>📁 Cấu trúc mã</h2>
<ul>
  <li><code>input.py</code> – Giao diện nhập dữ liệu với <code>ipywidgets</code>.</li>
  <li><code>run.py</code> – Mã chính để thực thi quá trình sao chép.</li>
</ul>

<h2>📝 Yêu cầu</h2>
<ul>
  <li>Python 3.x</li>
  <li>Google Colab (yêu cầu xác thực Google Drive)</li>
  <li>Internet để kết nối Google Drive API</li>
</ul>

<h2>📌 Giới hạn</h2>
<ul>
  <li>Chỉ hoạt động trong môi trường có quyền truy cập Google Drive qua API.</li>
  <li>Cần xác thực mỗi lần khởi động Colab mới.</li>
</ul>

<h2>🔐 Giấy phép</h2>
<p>Dự án chưa được gán giấy phép cụ thể.</p>

<hr>

<p>📦 Repo gốc: <a href="https://github.com/d4m-dev/Copy-Drive" target="_blank">https://github.com/d4m-dev/Copy-Drive</a></p>
