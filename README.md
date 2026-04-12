
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
        /* ヒーローエリアの背景設定（ここにバナー画像を設定してください） */
        .hero-bg {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?auto=format&fit=crop&q=80&w=2000');
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
            <!-- フォントサイズを大きく修正 -->
            <p class="text-xl md:text-3xl tracking-[0.2em] mb-6 opacity-90 font-serif">第3回 地域の交流会</p>
            <h1 class="text-4xl md:text-6xl font-serif mb-6 leading-tight">日進地域の未来を。<br>みんなで描く</h1>
            <!-- 会場名を削除 -->
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
    <section id="register" class="py-20 px-6 text-center">
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
            
            <p class="text-stone-500 font-medium">主宰：地域の交流会実行委員会</p>
        </div>
    </section>

    <!-- フッター -->
    <footer class="bg-stone-800 text-stone-400 py-8 text-center text-xs">
        <p>&copy; 2026 地域の交流会実行委員会</p>
    </footer>

</body>
</html>
