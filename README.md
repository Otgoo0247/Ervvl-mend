# Тэнгэр Эрүүл Мэнд — вэб хуудас

Vercel дээр байршуулах:

## Арга 1 — Vercel CLI (хамгийн хурдан)
1. Терминалаас энэ хавтас руу орно: `cd tenger-vercel`
2. Vercel CLI суулгана (нэг удаа): `npm i -g vercel`
3. Байршуулна: `vercel --prod`
4. Асуултад Enter дараад үргэлжлүүлнэ (шинэ project). Хэдэн секундын дараа таны live URL гарч ирнэ.

## Арга 2 — Vercel Dashboard (CLI хэрэггүй)
1. https://vercel.com/new руу орно (эсвэл бүртгэлгүй бол эхлээд бүртгүүлнэ)
2. "Deploy" хэсэгт энэ хавтсыг чирж тавина (drag & drop), эсвэл "Browse" дарж сонгоно
3. Vercel автоматаар static сайт гэдгийг таньж, index.html-ийг үндсэн хуудас болгоно
4. "Deploy" товч дарахад ойролцоогоор 10-20 секундэд live болно

## Арга 3 — GitHub-той холбох (тогтмол шинэчлэлт хийх бол)
1. Энэ хавтсыг GitHub repo болгож push хийнэ
2. https://vercel.com/new дээр тухайн repo-г import хийнэ
3. Framework Preset: "Other" гэж үлдээнэ (build command хэрэггүй, static файл)
4. Deploy дарна. Дараа нь GitHub-д push бүр дээр автоматаар шинэчлэгдэнэ

Файлын бүтэц:
- index.html — бүх контент, CSS нэг файлд (Vercel-д нэмэлт тохиргоо шаардахгүй)
- vercel.json — cleanUrls тохиргоо (заавал биш, гоё URL-ийн төлөө)
