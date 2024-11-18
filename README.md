# Svelte RoadMap

Lộ trình học **Svelte.js** cho người mới bắt đầu có thể được chia thành các giai đoạn sau đây, giúp bạn nắm vững kiến thức từ cơ bản đến nâng cao:

---

### **Giai đoạn 1: Làm quen với kiến thức cơ bản**
1. **Hiểu về JavaScript cơ bản**  
   - Biến, hằng, kiểu dữ liệu (`let`, `const`, `var`, `string`, `number`, `array`, `object`).
   - Vòng lặp, điều kiện, hàm (`if/else`, `for`, `map`, `filter`).
   - DOM Manipulation (`querySelector`, `addEventListener`).
   - Module ES6 (`import/export`).
   - Optional: Học TypeScript (có lợi cho các dự án lớn).

2. **Hiểu về HTML và CSS cơ bản**  
   - Cấu trúc HTML: Thẻ, thuộc tính, phân cấp.
   - CSS: Selector, box model, flexbox, grid.
   - CSS variables và keyframes (cho animation cơ bản).

---

### **Giai đoạn 2: Làm quen với Svelte.js**
1. **Tìm hiểu Svelte là gì**  
   - Svelte là một framework frontend hiện đại, **biên dịch trước (compile)** thành JavaScript gốc, không cần runtime nặng.
   - Đọc qua tài liệu chính thức: [https://svelte.dev/tutorial](https://svelte.dev/tutorial).  

2. **Cài đặt môi trường**  
   - Cài Node.js và npm/yarn.
   - Tạo dự án Svelte mới:
     ```bash
     npx degit sveltejs/template my-svelte-app
     cd my-svelte-app
     npm install
     npm run dev
     ```

3. **Hiểu cấu trúc cơ bản của một ứng dụng Svelte**
   - File `.svelte`: Kết hợp **HTML**, **CSS**, và **JavaScript** trong một file duy nhất.
   - Component cơ bản (tạo, import, export).
   - Reactive statements (`$:`).
   - Props (truyền dữ liệu giữa các component).

4. **Xây dựng ứng dụng đơn giản**  
   - Tạo một "To-Do App" với các chức năng thêm, sửa, xóa.
   - Sử dụng state reactivity (cách Svelte xử lý dữ liệu).

---

### **Giai đoạn 3: Làm việc với tính năng nâng cao**
1. **State Management trong Svelte**  
   - Sử dụng reactive stores (`writable`, `readable`).
   - Context API (chia sẻ dữ liệu giữa các component không liên quan trực tiếp).

2. **Routing và Navigation**  
   - Sử dụng thư viện `svelte-routing` hoặc `@sveltejs/kit` (nếu dùng SvelteKit).
   - Tạo các trang và điều hướng giữa chúng.

3. **Animation và Transition**  
   - Sử dụng các animation cơ bản của Svelte (`transition`, `animate`, `motion`).
   - Tự tạo animation tùy chỉnh.

4. **Fetch dữ liệu từ API**  
   - Sử dụng `fetch` để gọi RESTful API.
   - Kết hợp với reactive state để hiển thị dữ liệu.
   - Xử lý lỗi và trạng thái loading.

---

### **Giai đoạn 4: Chuyển sang SvelteKit (Full-stack Framework)**
1. **Tìm hiểu SvelteKit**  
   - SvelteKit là framework mạnh mẽ giúp phát triển ứng dụng full-stack (SSR, SPA, SSG).  
   - Bắt đầu với [https://kit.svelte.dev/](https://kit.svelte.dev/).

2. **Routing trong SvelteKit**  
   - Tạo các route động.
   - Data loading (`load` function).
   - SEO cơ bản (thêm metadata vào routes).

3. **API routes với SvelteKit**  
   - Tích hợp API trực tiếp trong SvelteKit.
   - Sử dụng các endpoint (`src/routes/api`).

4. **Triển khai ứng dụng**  
   - Sử dụng Vercel, Netlify, hoặc Render để deploy.

---

### **Giai đoạn 5: Thực hành dự án thực tế**
- **Dự án nhỏ:** Portfolio, Blog cá nhân, hoặc Quiz app.  
- **Dự án lớn:** Clone UI một trang web nổi tiếng (Netflix, Spotify).  
- **Dự án thực tế:** Thử kết hợp backend (Node.js, Flask, hoặc bạn đã dùng trước đây) với SvelteKit.  

---

### **Tài nguyên học tập**
1. **Tài liệu chính thức**  
   - [Svelte Tutorial](https://svelte.dev/tutorial)  
   - [SvelteKit Documentation](https://kit.svelte.dev/docs)

2. **Video hướng dẫn**  
   - Traversy Media: *Svelte Crash Course* ([YouTube](https://www.youtube.com/watch?v=zojEMeQGGHs))  
   - Net Ninja: *Svelte & SvelteKit Tutorials* ([YouTube](https://www.youtube.com/@NetNinja))  

3. **Khóa học trả phí (nếu cần)**  
   - Udemy: *Svelte.js - The Complete Guide (incl. Sapper.js)*  
   - Frontend Masters: *Introduction to Svelte*  

4. **Cộng đồng**  
   - Discord: [Svelte Discord](https://svelte.dev/chat)  
   - GitHub: Tìm các repo mẫu để học hỏi.  

