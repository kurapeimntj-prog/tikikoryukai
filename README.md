<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>第3回 地域の交流会：日進地域の未来を。みんなで描く</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;700&family=Shippori+Mincho:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans JP', sans-serif;
            scroll-behavior: smooth;
        }
        .font-serif {
            font-family: 'Shippori Mincho', serif;
        }
        /* ヒーローエリアの背景設定（Googleドライブの指定画像を設定） */
        .hero-bg {
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), 
                        url('https://lh3.googleusercontent.com/d/1-TUqy3hvtoqr8lh0Yjcbc0HUjKp7Ho7W');
            background-size: cover;
            background-position: center;
        }
        .accent-border {
            border-left: 4px solid #2d5a27;
        }
    </style>
</head>
<body class="bg-stone-50 text-stone-800">

    <!-- ヒーローセクション -->
    <header class="hero-bg h-[70vh] flex items-center justify-center text-white text-center px-4">
        <div>
            <p class="text-xl md:text-3xl tracking-[0.2em] mb-6 opacity-90 font-serif">第3回 地域の交流会</p>
            <h1 class="text-4xl md:text-6xl font-serif mb-6 leading-tight">日進地域の未来を。<br>みんなで描く</h1>
            <p class="text-lg md:text-xl font-light mb-8 font-serif">2026年5月9日(土) 18:00開始</p>
            <a href="#register" class="bg-[#2d5a27] hover:bg-[#1e3d1a] text-white px-8 py-4 rounded-full transition duration-300 font-bold shadow-lg inline-block text-lg">参加を申し込む</a>
        </div>
    </header>

    <!-- 紹介セクション -->
    <section class="max-w-4xl mx-auto px-6 py-16 md:py-24">
        <div class="accent-border pl-6 mb-12">
            <h2 class="text-2xl md:text-3xl font-serif mb-4 text-[#2d5a27]">なぜ人が住み続けるのか。<br class="md:hidden">その魅力と地域力を探る。</h2>
            <p class="leading-relaxed text-stone-600">
                大宮のすぐ北にありながら、独自の歴史と共同体文化を育んできた日進。宮原や土呂とは異なる「暮らしを整える街」としての魅力について、地域に住む人たちがと共に意見交換を行い、未来を描きます。
            </p>
        </div>
    </section>

    <!-- 開催概要セクション -->
    <section class="bg-white py-16 shadow-inner">
        <div class="max-w-4xl mx-auto px-6">
            <h3 class="text-center font-serif text-2xl mb-12">開催概要</h3>
            
            <div class="grid md:grid-cols-2 gap-12">
                <div class="space-y-6">
                    <div>
                        <h4 class="font-bold text-[#2d5a27] mb-1 text-lg">日時</h4>
                        <p>2026年5月9日(土)<br>第1部 18:00 - 19:00 (勉強会)<br>第2部 19:00 - 21:00 (懇親会・意見交換会)</p>
                    </div>
                    <div>
                        <h4 class="font-bold text-[#2d5a27] mb-1 text-lg">会場</h4>
                        <p>食べ処 さぼちゃん</p>
                        <p class="text-sm text-stone-600 mb-2">JR日進駅徒歩6分、JR宮原駅徒歩10分</p>
                        <a href="https://share.google/MoQddaJwO6g9JmTSc" target="_blank" class="text-blue-600 hover:underline text-sm">Googleマップで見る</a>
                    </div>
                    <div>
                        <h4 class="font-bold text-[#2d5a27] mb-1 text-lg">スピーカー</h4>
                        <ul class="list-disc list-inside space-y-2 text-stone-700">
                            <li>野原 健志 氏（日進桜まつり実行委員長）</li>
                            <li>吉成 竜之助 氏（日進大宮なび編集長）</li>
                            <li>片倉 淳平 氏（元さいたま市職員）</li>
                        </ul>
                    </div>
                </div>
                
                <div class="space-y-6">
                    <div class="bg-stone-100 p-6 rounded-lg shadow-sm border border-stone-200">
                        <h4 class="font-serif text-lg mb-3 text-[#2d5a27] border-b border-stone-300 pb-1">勉強会内容</h4>
                        <ul class="space-y-2 text-sm leading-relaxed text-stone-700">
                            <li>・日進桜まつりの立上げ経緯とイベント報告</li>
                            <li>・日進大宮なびと日進地域の歴史</li>
                            <li>・さいたま市北区の地域特性</li>
                        </ul>
                    </div>
                    <div class="bg-stone-100 p-6 rounded-lg shadow-sm border border-stone-200">
                        <h4 class="font-serif text-lg mb-3 text-[#2d5a27] border-b border-stone-300 pb-1">懇親会・意見交換会</h4>
                        <ul class="space-y-2 text-sm leading-relaxed text-stone-700">
                            <li>・参加者自己紹介</li>
                            <li>・勉強会内容の質問や意見交換</li>
                            <li>・楽しく交流</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 申し込みセクション -->
    <section id="register" class="py-20 px-6 text-center border-b border-stone-200">
        <div class="max-w-2xl mx-auto">
            <h2 class="font-serif text-2xl md:text-3xl mb-8">参加申込み</h2>
            <div class="mb-10 p-6 bg-green-50 rounded-lg border border-green-100">
                <p class="text-stone-700 leading-relaxed">
                    日進地域の未来を共に語り合いましょう。皆様のご参加を心よりお待ちしております。
                </p>
            </div>
            
            <div class="bg-white p-1 rounded-2xl shadow-2xl border-2 border-stone-200 overflow-hidden mb-8 max-w-md mx-auto">
                <div class="bg-[#2d5a27] text-white py-4 font-bold text-lg">
                    参加申込フォーム
                </div>
                <div class="p-8">
                    <p class="mb-6 text-sm text-stone-600">下記ボタンより、出欠をご回答ください。</p>
                    <a href="https://forms.gle/wA824BcxD6E3px3H6" target="_blank" rel="noopener noreferrer" class="inline-block w-full bg-[#2d5a27] hover:bg-[#1e3d1a] text-white px-12 py-5 rounded-full transition duration-300 font-bold text-xl shadow-md">
                        参加を申し込む
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- 公式LINEセクション -->
    <section class="py-20 px-6 bg-stone-100 text-center">
        <div class="max-w-2xl mx-auto">
            <h2 class="font-serif text-2xl md:text-3xl mb-4">最新情報を受け取る</h2>
            <p class="text-stone-600 mb-10">
                公式LINEでは次回の開催案内や活動報告をお届けしています。
            </p>
            
            <a href="https://qr-official.line.me/gs/M_517ynoyv_BW.png?oat_content=qr" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-3 bg-[#06C755] hover:bg-[#05b14c] text-white px-10 py-6 rounded-2xl transition duration-300 font-bold text-xl shadow-xl w-full max-w-md group">
                <svg class="w-8 h-8 fill-current" viewBox="0 0 24 24">
                    <path d="M24 10.304c0-5.369-5.383-9.738-12-9.738-6.616 0-12 4.369-12 9.738 0 4.814 4.269 8.846 10.036 9.608.391.084.922.258 1.057.59.155.398.102 1.026.05 1.429-.19 1.557-.84 6.003-.966 6.89-.147.933.511.564 1.057.213 1.059-.677 5.727-3.483 7.82-5.891 1.616-1.846 2.861-3.8 3.007-5.845.047-.655.047-1.319.047-1.922zm-15.59 3.291c0 .421-.34.762-.761.762-.421 0-.762-.341-.762-.762v-4.522c0-.422.341-.762.762-.762.421 0 .761.34.761.762v4.522zm3.307 0c0 .421-.34.762-.761.762-.19 0-.363-.07-.492-.185l-1.547-1.392v.815c0 .421-.341.762-.762.762-.421 0-.762-.341-.762-.762v-4.522c0-.422.341-.762.762-.762.421 0 .762.34.762.762v.815l1.547 1.392v-.815c0-.422.341-.762.762-.762.421 0 .761.34.761.762v4.522zm3.307 0c0 .421-.34.762-.761.762h-1.785c-.421 0-.762-.341-.762-.762v-4.522c0-.422.341-.762.762-.762.421 0 .761.34.761.762v3.76h1.024c.421 0 .761.341.761.762zm3.307 0c0 .421-.34.762-.761.762h-1.785c-.421 0-.762-.341-.762-.762v-4.522c0-.422.341-.762.762-.762h1.785c.421 0 .761.34.761.762s-.34.762-.761.762h-1.024v.748h1.024c.421 0 .761.341.761.762s-.34.762-.761.762h-1.024v.74h1.024c.421 0 .761.341.761.762z"/>
                </svg>
                <span>公式LINEを追加する</span>
            </a>
            
            <p class="mt-12 text-stone-500 font-medium italic">地域の交流をもっと身近に、もっと楽しく。</p>
            <p class="text-stone-500 font-medium">主宰：地域の交流会実行委員会</p>
        </div>
    </section>

    <!-- フッター -->
    <footer class="bg-stone-800 text-stone-400 py-8 text-center text-xs">
        <p>&copy; 2026 地域の交流会実行委員会</p>
    </footer>

</body>
</html>
