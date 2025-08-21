export default function Home() {
  return (
    <main style={{ padding: "2rem", fontFamily: "sans-serif" }}>
      <h1>(주) 풍성공영</h1>
      <p>우레탄 뿜칠 · 건축 방수 · 바닥 공사 전문 시공업체</p>

      <h2>시공 의뢰</h2>
      <form method="POST" action="https://formspree.io/f/mnqeylwb">
        <input type="text" name="name" placeholder="성함" required />
        <input type="tel" name="phone" placeholder="연락처" required />
        <textarea name="message" placeholder="시공 요청 내용을 적어주세요" />
        <button type="submit">보내기</button>
      </form>
    </main>
  );
}import './globals.css';

export const metadata = {
  title: '(주) 풍성공영',
  description: '우레탄 뿜칠 · 방수 · 바닥 공사 전문업체',
};

export default function RootLayout({ children }: { children: React.ReactNode }) {
  return (
    <html lang="ko">
      <body>{children}</body>
    </html>
  );
}
{
  "name": "pungsunggongyoung-website",
  "version": "1.0.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "14.2.3",
    "react": "18.2.0",
    "react-dom": "18.2.0"
  }
}
