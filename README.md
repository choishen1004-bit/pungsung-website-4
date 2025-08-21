[page.js](https://github.com/user-attachments/files/21920668/page.js)
export default function Home() {
  return (
    <main style={{ textAlign: "center", padding: "50px" }}>
      <h1>(주) 풍성공영</h1>
      <p>우레탄 뿜칠 및 건축 시공 전문 기업</p>
      <p>시공 의뢰 및 상담을 원하시면 아래 버튼을 클릭하세요.</p>
      <button style={{ marginTop: "20px", padding: "10px 20px" }}>시공 의뢰하기</button>
    </main>
  );
}[package.json](https://github.com/user-attachments/files/21920670/package.json){
  "name": "pungsunggongyoung",
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
    "react-dom": "18.2.0",
    "tailwindcss": "3.4.1"
  }
}

