# Reading List — 需要側フロンティアの先行論考

AI が実装コストを溶かした後の「望む力」の枯渇と、価値の移動先に関する既存の有名エッセイ・論考のリンク集。

- 収集: 2026-08-14。全 URL は同日に WebSearch / WebFetch で実在・内容照合済み（[unverified] 表記の 2 件のみ、fetch がブロックされたため書誌レベルの確認に留まる）。2026-08-16〜17 追加分（Borretti 5 本 / Imas 系列 / 翻訳 §8 / HN 定点 / 日本語圏 5 本）は desire line が内容照合、2026-08-17 に URL 実在を再確認。2026-08-18 追加分（公開の停止 3 本 / Imas 2026-02-09 / Show HN 定点）も同日照合（Medium は curl 403 = bot 遮断のため run 側の一次確認に依拠）。2026-08-19 追加分（Show HN 到達率 / HN メタ議論 / lcamtuf）は同日 URL 照合・Algolia 数値を再取得して再現確認
- 起点エッセイ: [AI に頼みたいことが尽きたあと、ひとつだけ残った欲望](https://note.com/sakamaki4228/n/n2375bfc4d521)（note, 2026-08-13）
- LLM 界隈の論考は陳腐化が速い。日付ごと読むこと

## 1. 古典 — 余暇と欲望の問題

- **Economic Possibilities for our Grandchildren** — John Maynard Keynes (1930)
  https://www.marxists.org/reference/subject/economics/keynes/1930/our-grandchildren.htm
  経済問題が解決した後、人類は「科学と複利が勝ち取った余暇をいかに賢く生きるか」という初めての本当の問題に直面すると予言。本テーマの原点。

- **In Praise of Idleness** — Bertrand Russell (1932)
  https://files.libcom.org/files/Bertrand%20Russell%20-%20In%20Praise%20of%20Idleness.pdf
  「働きすぎは美徳ではない」と論じ、余暇を賢く使う能力は文明と教育の産物であって自動的には得られないと指摘。（Harper's 初出はペイウォールのため PDF 版）

- **自由からの逃走 (Escape from Freedom)** — エーリッヒ・フロム / 日高六郎訳（1941、邦訳 1951）
  http://www.tsogen.co.jp/np/isbn/9784488006518
  自由（= 何でも選べる状態）が人間に不安と空虚をもたらし、人は自由から逃走するという古典。生産制約が消えた後の「積極的自由」の困難さがテーマに直結。[unverified]

- **暇と退屈の倫理学** — 國分功一郎（2011、新潮文庫 2021）
  https://www.shinchosha.co.jp/book/103541/
  「暇」を得た人間はなぜ退屈に苦しむのかを、パスカル〜ハイデガー〜消費社会論を通じて考察。「頼むことが尽きた」状態の哲学的な先行考察として最重要の日本語書籍。

- **The Burnout Society（疲労社会）** — Byung-Chul Han（2010、英訳 2015）
  https://www.sup.org/books/theory-and-philosophy/burnout-society
  規律社会から「達成社会」への移行で、人間は外的強制なしに自己搾取するようになったと論じる。「できる」が無限化した世界での疲労と空虚の理論。[unverified]

- **Secrets about People: A Short and Dangerous Introduction to René Girard** — Alex Danco (2019)
  https://alexdanco.com/2019/04/28/secrets-about-people-a-short-and-dangerous-introduction-to-rene-girard/
  ジラールの模倣的欲望の入門論考。「我々はモノを欲しがるのではなく、誰かに成りたがる」— 欲望が内発せず他者から借りられるという理論は「望む力の枯渇」の構造的説明になる。**注（2026-08-17）**：同じ Girard から正反対の結論（欲望は他者から湧き続けるので飽和しない）を実験データ付きで出す系譜が §4 Imas。枯渇を説明する道具か、枯渇を否定する道具か——Girard は両刃（[concepts.md](concepts.md) 対抗モデル節）。

## 2. taste — 判断がボトルネックになる論

- **Age of Taste** — Shyamal Anadkat (2025-06-25)
  https://shyamal.me/blog/age-of-taste/
  「試すコストが崩壊すると、ボトルネックは何を試すかを知ることになる」。無限の生成能力を与えられてもハムレットを選び出せるのはシェイクスピアの鑑識眼だけ、という思考実験。

- **When AI Has Better Taste Than You** — Julie Zhuo (2025-06-24)
  https://joulee.medium.com/when-ai-has-better-taste-than-you-0dc8e870db9a
  taste すら AI に追い抜かれつつあると認めた上で、最後に残る人間の優位は agency（価値観に従って行動する意志）だと論じる。taste 論と agency 論の橋渡しになる一本。

- **When Everyone Can Make, Taste Is All That's Left** — Mike Litman / Taste Machines (2026-03)
  https://tastemachines.com/essays/taste-is-all-thats-left
  「AI は実行できるが、味わえない (AI can execute. AI cannot taste.)」。制作スキルの希少性が消えた後、何を作る価値があるかの判断が最後の競争優位になるとする。

- **Taste Is the Next Capability AI Will Crack** — Wenbo Pan (2026-06-12)
  https://www.wenbo.io/blog/taste-scaling/
  カウンターポイント。研究 taste（どの問題を追うべきかの判断）自体が自動化曲線に乗っていると実測を示す。「taste が最後の砦」論への反証。

## 3. agency — 望む力がボトルネックになる論

- **Human Bottlenecks** — Fernando Borretti (2026-05-18)
  https://borretti.me/article/human-bottlenecks
  AI 増強が効かない理由を「serious context of use（本気の使用文脈）の欠如」と内的認知ボトルネックに求める。抽象的な願望と、動かすべき針を持つ具体的必要との落差を突く。起点エッセイが最も近いと評した論考。

- **Borretti 2026 年後半 5 本**（2026-08-16 追加。定点の「変化なし」記録が false negative で、Human Bottlenecks 以降に 6 本公開されていた。うち "The Contracting Circle"（2026-08-07、LLM の人格性）は本 line 外につき未収録）
  - **Mathematics Without Mathematicians** (2026-08-02) https://borretti.me/article/mathematics-without-mathematicians
    **第四の機構「受け手の消失」の定式化**。「趣味で数学をやればいい」という逃げ道を潰す——"very, very few people can sustain any activity long-term on the basis of intrinsic motivation alone. We are social animals: we care about being useful, about status, about outcomes in the world." そして "if I design a new language, will anyone care?"。[concepts.md](concepts.md) 受け手の消失
  - **When The Future Doesn't Need Us** (2026-07-28) https://borretti.me/article/when-the-future-doesnt-need-us
    **この repo の中心関心を明示的に格下げする論考**。"When people talk about AI taking jobs, the main problems they worry about are poverty and meaning, but I think more people should be worried about disempowerment." 望みが尽きる前に、望みを実行に移す物質的な力の方が先に失われるなら、需要側フロンティアは構造的に到達されない。2026-08-16 時点で反駁材料なし（Imas の関係部門論が対抗筋を一本立てるのみ）
  - **Review: Job-Less Utopia** (2026-08-03) https://borretti.me/article/review-job-less-utopia
    post-work の欲望の行き先を扱う書評。未精読
  - **Human Routers of Machine Words** (2026-06-13) https://borretti.me/article/human-routers-of-machine-words
    実行そのものが価値である論。未精読
  - **No-One Escapes the Permanent Underclass** (2026-06-25) https://borretti.me/article/no-one-escapes-the-permanent-underclass
    agency の消失。人間は「はるかに強力な機械の、agency を持たない無力なペット」。disempowerment 論の反復、意味は扱わない
  - 定点（2026-08-19）：インデックスに **"AI Alignment as a Thought-Terminating Cliche"（2026-08-18）** を検出。slug 推測 fetch は 404 で本文未取得。タイトルからは本 line 外の公算が高いが、タイトルだけで落とさず持ち越し

- **Tool-makers usually lack connection to a serious context of use** — Andy Matuschak (Evergreen note)
  https://notes.andymatuschak.org/z7vdiuQK7HuFyi4V5EemF3e
  "serious context of use" 概念の出典ノート。道具は本気の創作的必要から切り離されると空転する。姉妹ノート: https://notes.andymatuschak.org/People_who_write_extensively_about_note-writing_rarely_have_a_serious_context_of_use

- **The Gentle Singularity** — Sam Altman (2025-06-11)
  https://blog.samaltman.com/the-gentle-singularity
  frontier lab 側の abundance 論。知能が無限に近づいても人間の欲望は基本的に不変で無限、という需要側の楽観を代表する（本プロジェクトの仮説への対立仮説として重要）。

- **Machines of Loving Grace** — Dario Amodei (2024-10)
  https://darioamodei.com/essay/machines-of-loving-grace
  第 5 節「Work and Meaning」が該当。AI がほぼ全ての経済的価値あるタスクをこなす世界で、意味は経済的労働ではなく人間関係に由来すると論じる。

- **AI時代、「作れる」より「何を作るか」が面白くなってきた** — muu3 / Qiita (2026-06-05)
  https://qiita.com/muu3/items/19f39c1f113830e3d902
  実装コスト低下でボトルネックが「何を作るか」の意思決定へ移ったことを、一人称の実務経験から論じる日本語記事（枯渇ではなくポジティブな再定義の側）。

- **AIが実装までやるようになって、エンジニアとして何が残るのか（2026年8月）** — tsuyuki makoto (2026-08-09)
  https://www.tsuyukimakoto.com/blog/2026/08/09/engineer_strength_in_the_ai_era_202608/
  「何を作るかは人間に残る」定型句側の **3 本目**（muu3 2026-06-05、yminabe 2026-08-14 に続く）。「考えたことを書き起こさなければ完成しないが、私にとって一番面白い部分はすでに終わっている」と実装の委譲を歓迎する。この定型句がいつ誰に裏切られるかの watch の分母。2026-08-17 追加。

## 4. post-scarcity — 希少性と価値の移動

- **AI doesn't end scarcity. It relocates it** — François Candelon ほか / Fortune (2026-07-24)
  https://fortune.com/2026/07/24/ai-doesnt-end-scarcity-it-relocates-it/
  希少性は消えず、下方（水・電力等の物理入力）と上方（判断、名前を賭ける保証、視聴者の夜の時間）へ移動すると論じる。「competent text はほぼ無料になったが、それが代理していた判断は希少なまま」。

- **AI Doesn't Remove Scarcity, It Shifts It** — Robert Bernhardt / Crooked Dandy (2025-07-25)
  https://crookeddandy.substack.com/p/ai-doesnt-remove-scarcity-it-shifts
  豊穣化した領域から需要は次の希少性（地位・望ましい空間・本物の人間的つながり・注意）へ移るとし、「何が豊かになった時に何が希少になるか」を見抜くことが機会の鍵と論じる。定点判定（2026-08-18）：最終投稿 2025-09-28 で約 11 ヶ月更新なし。**定期確認から外す**（削除はしない）。

- **When Intelligence Becomes Abundant, What Becomes Scarce?** — Graeme Smith (2026-06-01)
  https://thisisgraeme.me/2026/06/01/what-becomes-scarce-when-intelligence-becomes-abundant/
  知能豊穣後の 5 つの希少資源（判断・信頼・能力・ガバナンス・意味）を整理。「AI は既に燃えているものに燃料を注ぐ」— 望むものを持たない者には増幅すべきものがない、という含意。定点確認（2026-08-17）：この後に 2026-06-09「AI は能力を創造しない。増幅するだけだ」、2026-06-22「知能経済に誰が参加し、どのような条件下で参加するのか」の 2 本あり。2026-08-18 にさらに "The Human Operating Envelope"（SIGNAL 006, 2026-07-29）を検出。**3 本とも未精読**。

- **What will be scarce?** — Alex Imas / Ghosts of Electricity (2026-04-14)
  https://aleximas.substack.com/p/what-will-be-scarce
  **対立仮説（欲望は飽和しない）の実験データ付き正本候補**（2026-08-17 追加）。シカゴ大ブースの行動経済学者が Girard の模倣的欲望を土台に、AI 時代の希少性を三段で組む——構造変化・非同次的需要（Comin–Lashkari–Mestieri, Econometrica 2021）・mimetic desire（欲望は相対的なので飽和しない）。希少になるのは**関係部門**（教師・看護師・セラピスト・接客・聖職者——人間であること自体が価値の一部である労働）。需要崩壊シナリオを名指しで否定。`desire exhaustion` の在庫モデルに対する**フローモデル**（[concepts.md](concepts.md) 対抗モデル節）。紹介ページ: https://futuretech.mit.edu/news/what-will-be-scarce （MIT FutureTech, 2026-04-14）

- **Alex Imas and Phil Trammell – What remains scarce after AGI?** — Dwarkesh Podcast (2026-06-04)
  https://www.dwarkesh.com/p/alex-imas-phil-trammell
  Imas × Mandel の追試の定性的な一次発言——"the person-produced art print is valued much higher than the AI version"、500 部刷ると "the price goes down a lot because it's no longer seen as making a connection with this one artist"。**Trammell の反論**（飽和回避は模倣でなく財の種類の拡大）と Imas 自身の条件付き悲観（"if there is no such increasing variety in the human sector ... It goes to zero"）も同じ対談内。Imas の枠組みは一枚岩でない。

- **How Human Psychology Explains Exclusive Brands and Exclusionary Policies** — Chicago Booth Review (2021-01-13)
  https://www.chicagobooth.edu/review/how-human-psychology-explains-exclusive-brands-and-exclusionary
  Imas–Madarász の mimetic dominance-seeking 実験の報道。同一の私的財のオークションで参加者の一部をランダムに排除すると、残りの入札額が上がる（第二実験でランダム排除群の中央値 5 ドル、対照群の 2 倍）。Girard への依拠を明示。原論文は Working paper "Mimetic Dominance and the Economics of Exclusion" (2020-07) → NBER w30334 "Superiority-Seeking and the Preference for Exclusion" https://www.nber.org/papers/w30334 （実在確認 2026-08-17。Review of Economic Studies 2024 掲載と報じられるが一次確認できていない）

- **The economist who was terrified of AI just found a rare reason for hope** — Fortune (2026-04-19)
  https://fortune.com/2026/04/19/alex-imas-human-jobs-ai-economy-chicago-economist-substack-doomsday-scenario/
  Imas 論考の報道。Imas × Mandel の AI 関与作品の実験を定性的に伝える。数値（人間作の排他性プレミアム 44% 対 AI 作 21%）の出所は The Neuron Daily https://www.theneurondaily.com/p/what-gets-scarce-when-ai-does-everything （**二次情報**。一次論文には未到達 — 到達したら差し替え）

- **Someday we will all be artists** — Alex Imas / Ghosts of Electricity (2026-02-09)
  https://aleximas.substack.com/p/someday-we-will-all-be-artists
  タイトルは制作側に見えるが**消費側の議論**。中心は humanness premium（観客は成果物だけでなく作り手との関係・物語・来歴を買う）。作り手がなぜ作りたくなるかは "incentives matter" の一段落のみで、制作欲望の理論も制作側の模倣的欲望の議論も無い。「Imas の実証は消費側のみ」（[concepts.md](concepts.md) 対抗モデル節）の空白確認。2026-08-18 精読。同 archive の未読 2 本（"How Will AI-driven Automation Actually Affect Jobs?" 2026-03-23 / "Who Uses AI (and How)?" 2026-02-18）は 2026-08-19 検出・未精読。

- **The Intelligence Age** — Sam Altman (2024-09-23)
  https://ia.samaltman.com/
  "intelligence too cheap to meter" 路線の原典的ポスト。需要側の空洞化には触れない点も含めて資料価値がある。

## 5. 一人称の証言・体験記（最重要・最も希少）

- **Eight years of wanting, three months of building with AI** — Lalit Maganti (2026-04-05)
  https://lalitm.com/post/building-syntaqlite-ai/
  8 年間温めた欲望を AI エージェントで 3 ヶ月で実現した一人称記録。希少だったのは欲望ではなく実行能力だった、という「望みの在庫」がまだある側の証言。HN 議論: https://news.ycombinator.com/item?id=47648828

- **Vibe Coding Makes Me Feel Empty Inside** — Headmonk (2026-07-08)
  https://medium.com/@headmonk/void-coding-9214ea07261d
  AI コーディングで生産性が上がったのに感情的に空洞化したという一人称の告白。「プロジェクトが AI 速度で動き出すと、『自分は本当にこれを気にかけているのか』と問う暇がなくなる」。

- **My Existential AI Crisis** — Max Karson (2024-02-24)
  https://mrgirl.substack.com/p/my-existential-ai-crisis
  「私は必要とされなくなる。誰からも、何のためにも」— AI が自分の能力を無用化することへの dread を綴った一人称エッセイ。虚無の到来を先取りした証言。

- **If AI Did Everything, What Would We Do?** — Waleed Mahmud (2024-09-19)
  https://waleedmahmud.substack.com/p/if-ai-did-everything-what-would-we
  労働が不要になった後の自分を一人称で叙述する思弁エッセイ。「自分のアイデンティティがどれほど『何かをすること』に包まれていたか気づいていなかった」。純粋な体験記ではなく一人称形式の思弁である点に注意。

- **AIが奪ったのはエンジニアの「仕事」ではなく「情熱」だった** — ぽろり / @IT (2026-01-21)
  https://atmarkit.itmedia.co.jp/ait/articles/2601/21/news008.html
  AI が「能動的な試行錯誤」というエンジニアリングの最も楽しい部分を奪ったと論じる日本語コラム。厳密な一人称告白ではないが、日本語圏でこのテーマに最も近い公開文章。

- **2026年8月、開発の仕事が減るとは思っていたけど、想像よりだいぶ早かった** — Yoji Minabe / Qiita (2026-08-14)
  https://qiita.com/yminabe/items/b8330209ba90dd148cdc
  仕事の消失を扱う日本語一人称記事。「脳みそが死んでいく感じがする」（空洞化）「お見合いで職業を説明できなくなってきた」（無用化 dread）が型に触れるが、「何を作るか・なぜ作るか」は人間に残ると信じる側で枯渇型ではない（muu3 系譜のポジティブ再定義）。2026-08-15 内容照合済み。

- **僕が AI にコーディングをさせなくなった理由（2026 年 5 月版）** — nishiken / Zenn (2026-06-01)
  https://zenn.dev/nishiken_zenn/articles/why-stopping-coding-for-ai-ja
  枯渇でも受け手の消失でもない。理由は実務的——自分で書く機会が減って副産物的な成長投資を手放した、非エンジニアの「これできる？」に即答できなくなった、レビュー工数より人が書く方が速いケースがある。「AI を完全に捨てたのではありません」。**実行への執着を意図的に再建した例**——経路仮説の「緩衝材の再装着」として読める材料（解釈であって実証ではない）。2026-08-16 追加。

- **個人開発はオワコンなのか？2026年に感じた現実** — @elliot_james / Qiita (2026-06-03)
  https://qiita.com/elliot_james/items/1c29989205b0c998c9ff
  「私自身も個人開発を続けていますが」——動機は健在で枯渇型ではない。だが「多くの個人開発者が苦労するのは開発ではなく**集客**です」——AI で参入障壁が下がり「作れば使われる」が成立しなくなった。**受け手の消失の分析**であって、それで動機を失った証言ではない。日本語圏で次に裏切られる定型句は「何を作るかは人間に残る」ではなく「作れば誰かが使う」かもしれない、という観測の起点。2026-08-16 追加。

- **個人開発はなぜ誰も使わないのか──AIで「作る壁」が消えた時代に大事になること** — ゆんぼう (yun_bow) / Zenn (2026-06-14)
  https://zenn.dev/yun_bow/articles/6e6bcbf127072a
  **「受け手の消失」機構の日本語圏における最初の明示的記述**。「動くものができた。GitHub に push した。Product Hunt にも出した。——でも、誰も使わない」から始め、AI で「作る壁」は下がったが「見つけられる壁」「信頼される壁」はむしろ上がったと論じる。著者自身が「実務的な考察・仮説であり、定量的に証明された法則ではない」と明記——**告白ではなく分析**。「作れば誰かが使う」を正面から否定する文章が日本語圏に既に存在する証拠。2026-08-17 追加。

- **誰でも作れる時代に個人開発をする意味** — ktg / Zenn (2026-01-24)
  https://zenn.dev/ktg/articles/598f57c39eb1d9
  「『誰でも作れる』からこそ、逆に悩みが生じます。自分が作る必要がないんじゃないか？」——判別質問 2 で「取られた」側＝**剥奪型**。ただし「需要は存在する」で決着しており、告白ではなく再定義。2026-08-17 追加。

- **I hate AI side projects** — Dylan Castillo (2026-02-20)
  https://dylancastillo.co/posts/ai-side-projects.html
  **「公開の停止」型の最も明確な一本**（[concepts.md](concepts.md) 語彙節）。"I still work on side projects. But now I dread sharing them." 理由は飽和（"The best thing about AI is that EVERYONE can build now. The worst thing about AI is that EVERYONE can build now."）、見分けがつかない（"All landing pages and GitHub repos look the same." "The signal-to-noise ratio is unbearably low."）、過去作の事後的減価（"Most of my past side projects would take me a few minutes or hours to build with Claude Code. Today, they're not worth talking about."）。受け手としても撤退（"I rarely look at projects on Hacker News, Reddit, or X anymore"）——作り手と受け手の撤退が同一人物内で同時。side project＝非生計依存層で、「釣れる語彙は枯渇ではなく公開・共有・見せるの側」という探索知見の出所。2026-08-18 追加。

- **AI is slowly munching away my passion** — dzervas / WhyNot.Fail (2026-02-15)
  https://whynot.fail/human/ai-is-slowly-munching-away-my-passion/
  ギリシャのセキュリティ／インフラ系エンジニア。失ったのは成果物でも作業でもなくアイデンティティと信用——"I used to be 'the guy that automates stuff'"、そして **"My life's work 'might be AI.'"**（AI が存在しなければ成立しない文＝AI 特異的）。GitHub リポジトリ群が人と繋がる手段として機能しなくなった（"I used very often to connect, to start conversations, to exchange knowledge"）——**mimetic 断絶の制作側の一人称記述**。対処は個人プロジェクトでのエージェント使用停止＝nishiken と同じ行動だが理由が社会的（自分のものだと認められなくなるから）。2026-08-18 追加。

- **AI took my job, my hobby, and left me with the dishes** — Raz / Medium (2025-06-26)
  https://medium.com/@ravzeex0/ai-took-my-job-my-hobby-and-left-me-with-the-dishes-f34dc30f37c9
  素直な剥奪型。デザイン／開発が職業、絵が趣味——"she followed me there too" "She's better at that too."。価値は型でなく、**趣味（非生計依存）の側でも剥奪が起きる**実例である点——生計依存は剥奪の有無を決める変数ではない（[concepts.md](concepts.md) 翻訳節の変数を一段弱める）。2026-08-18 追加。

## 6. 実証研究 — 隣接現象の量的測定（2026-08-15 追加）

エッセイ genre の外にある査読済み文献群。**空洞化と剥奪**（[concepts.md](concepts.md) 境界節）は n=数百〜数千で測定済み。ただし全て「与えられたタスク」を割り当てる実験パラダイムで、**枯渇（何を望むかが尽きる）は原理的に測れない設計** — この構造的空白が、本 repo の証言収集という手法の積極的根拠になる。全 URL は 2026-08-15 に内容照合済み。

- **Relying on AI at work reduces self-efficacy, ownership, and meaning while active collaboration mitigates the effects** — Lee, Yin, Jia, Wakslak / Scientific Reports 16:13583 (2026-03-15)
  https://pmc.ncbi.nlm.nih.gov/articles/PMC13121737/
  事前登録実験 N=269 + 追跡 N=270。受動的 AI 使用で所有感 -19% / 意味 -11% / 効力感 -8%。AI なし作業に戻っても効力感 -12% / 意味 -8% が残存。能動的協働（自分で下書き→AI 推敲）では低下せず。報道: https://phys.org/news/2026-06-passive-ai-meaninglessness.html

- **Human-generative AI collaboration enhances task performance but undermines human's intrinsic motivation** — Wu et al. / Scientific Reports (2025-04-29)
  https://pmc.ncbi.nlm.nih.gov/articles/PMC12041296/
  4 実験・総 N=3,562。AI 協働は即時成績を上げるが単独作業には持続せず、復帰後に内発的動機が低下し**退屈**が上昇（psychological deprivation effect）。國分『暇と退屈の倫理学』の対象が実験心理学の従属変数になった接続点。

- **When AI Sparks Less: Generative AI and The Decline Of Self-Perceived Creativity** — Endres, Schöttl, Baisch / ECIS 2026 (2026-06-14)
  https://aisel.aisnet.org/ecis2026/genai/genai/5/
  N=82。生成 AI 使用で内発的動機・創造性関連スキルが低下する一方、**自己評価の成績は不変** — 低下が本人に見えない可能性を示唆し、一人称証言という測定器の限界に触れる。

- **Are We Automating the Joy Out of Work? Designing AI to Augment Work, Not Meaning** — Ranjit, Zhou, Swayamdipta, Quercia / CHI 2026 (arXiv 2603.14963)
  https://arxiv.org/html/2603.14963
  **剥奪機構の本命**。202 労働者 + 197 開発者・171 タスク・22 職種（LLM で 10,131 タスク・512 職種へスケール）。労働者は無意味なタスク（Perceived Bullshitness 高）を委譲したがり意味側を保持したがるのに、意味・agency の高いタスクほど AI 露出が高い。`desire exhaustion` に対する競合仮説の最初の外部証拠。

- **Octoverse: A new developer joins GitHub every second as AI leads TypeScript to #1** — GitHub Blog (2025-10-28 公開 / 2026-02-28 更新、観測窓 2024-09〜2025-08)
  https://github.blog/news-insights/octoverse/octoverse-a-new-developer-joins-github-every-second-as-ai-leads-typescript-to-1/
  マクロ需要側の反対材料。新規リポジトリ毎分 230 個（年約 1.21 億）、新規開発者 3,600 万人 (+23% YoY)。「作りたいもの」の供給はマクロで加速中 — 枯渇仮説の一般化射程を狭める、毎年更新される定点指標（次回 2026 年 10 月末前後見込み）。

- **Hacker News "Ask HN: What are you working on?" 月次スレッド系列**（Algolia API 経由、2026-08-16 初取得）
  https://hn.algolia.com/api/v1/search_by_date?tags=story&query=%22What%20are%20you%20working%20on%22&hitsPerPage=30
  **二本目のマクロ反証器**。コメント数（プロジェクト数の proxy）は 2025-12 にピーク 1,470 を打ち、2026-02〜08 は **1,121〜1,189 の狭い帯に完全に横ばい**（6 ヶ月で変動幅 5.7%）。Octoverse が「加速」、こちらは「横ばい」——枯渇のマクロ兆候なし、加速もなし。留保：コメント数≠プロジェクト数、2025-12 は年末季節性の可能性、2026-01 は API 欠損。item ページ直取得は 429 が出やすく、Algolia API が確実（手順知見）。次の観測点は 2026-09 スレッド。2026-08-18 時点 1,195（帯 1,121〜1,195 を出ない）。

- **Show HN 投稿数（7 月同月比、3 年）**（Algolia API `tags=show_hn` + `numericFilters=created_at_i`、2026-08-18 初取得）
  https://hn.algolia.com/api/v1/search_by_date?tags=show_hn&numericFilters=created_at_i%3E1782864000,created_at_i%3C1785542400&hitsPerPage=1
  **三本目のマクロ反証器、かつ最も直接的**。1,586（2024-07）→ 2,567（2025-07）→ 4,199（2026-07）、2 年連続 +62〜64%/年——公開行為はマクロで加速中。「公開の停止」を集計は一切映さない。Show HN タグは自己申告。2026-08-19：全クエリで `exhaustiveNbHits: true` を確認——**概算留保は反故、全数**。

- **Show HN 到達率（7 月同月比、3 年）**（Algolia API `tags=show_hn` + `points>=N`、2026-08-19 新設。数値は同日に再取得して再現）
  https://hn.algolia.com/api/v1/search_by_date?tags=show_hn&numericFilters=created_at_i%3E1782864000,created_at_i%3C1785542400,points%3E=100&hitsPerPage=1
  **この repo で初の「受け手の消失／希釈」の定量指標**。投稿 1,586 / 2,567 / 4,199（+165%）に対し、10 点以上 244 / 274 / 398（+63%）、**100 点以上 70 / 61 / 71（+1.4%）**。到達率：10 点 15.4% → 10.7% → 9.5%、**100 点 4.41% → 2.38% → 1.69%**（相対 −62%）。参考：HN 全 story の 100 点以上は 1,063 / 1,163 / 1,350（+27%）で、Show HN の取り分は 6.59% → 5.24% → 5.26%——注意の総量は増えたのに Show HN は拡張分を取れていない。**消失ではなく希釈**（[concepts.md](concepts.md) 受け手の消失）。因果は作り手急増・AI 言説の枠占拠・モデレーションの重ね合わせで未分離、venue は 1 つ。

- **Show HN 同一人物継続率**（2026-08-19 新設・即座に格下げ）
  https://hn.algolia.com/api/v1/search_by_date?tags=show_hn,(author_gurachek,author_ozten,author_Jsuh,author_Suedish,author_scrollaway,author_eddieos,author_pmbanugo,author_quinto_quarto,author_javier_cardona,author_siim,author_joaomeloplus,author_FakeFind_ai,author_CarSan99,author_delduca,author_johntawfik,author_averadev,author_yiyingzhang)&numericFilters=created_at_i%3E1767225600&hitsPerPage=100
  2024-07 コホート 21.5%（17/79）→ 2025-07 コホート 20.6%（14/68）、翌年 1/1〜8/19 の同位相窓。差 0.9 pt は誤差 ±13 pt の内側。HN は投稿の約 70% が一度きりのアカウント（基底離脱率 79%）なので、**author 単位の指標は原理的に感度を持たない**。「公開の停止」の検出器として使えないと判定。

- **The percentage of Show HN posts is increasing, but their scores are decreasing** — plastic041 / Hacker News（237 点、2026 年初頭）
  https://news.ycombinator.com/item?id=46702099
  当事者コミュニティ側から同じ現象（Show HN 比率増・スコア減）を記述した HN 投稿。受け手側の**制度的反応**の観測点。関連：**Ask HN: Please restrict new accounts from posting** — Oras（2026-03-08、721 点・515 コメント、id=47300329）— AI 由来の低品質投稿を理由に新規アカウントの投稿制限を要求。二次報道 https://keydiscussions.com/2026/03/09/hacker-news-moves-toward-restricting-show-hn-posts-amid-the-ai-slop-wave/ （Key Discussions 2026-03-09）は運営の Show HN throttling 言及を伝えるが、**実装の一次証拠は未確認**。watched-sources 追加候補。

- **How much of HN is AI?** — lcamtuf (2026-03-12)
  https://lcamtuf.substack.com/p/how-much-of-hn-is-ai
  HN 日次トップ記事に占める AI 関連・AI 生成の比率が 2026-02 の約 40% → 06 の 50〜60%（Pangram + サンプリング）。Show HN が 100 点枠を取れなくなった原因の候補（受け手が個人開発に飽きたのでなく、**同じ枠を AI 言説が占めた**）。到達率低下の交絡として分離が要る。HN の AI 汚染比率を実測している唯一の定点、watched-sources 追加候補。

## 7. 将棋 — 先行完走ドメインの資料（2026-08-15 追加）

AI 優位確定（2017）から約 10 年経過した将棋を、経路仮説の遡及検証ドメインとして登録（理論上の位置付けは [concepts.md](concepts.md) 将棋節、発掘の段取りは [testimonies.md](testimonies.md)）。URL は 2026-08-15 照合済み。

- **不屈の棋士** — 大川慎太郎（講談社現代新書、2016-07-20）
  https://bookclub.kodansha.co.jp/product?item=0000210864
  「人工知能に追い詰められた『将棋指し』たちの覚悟と矜持」。現役棋士 11 人（羽生善治・渡辺明ら）の剥奪期インタビュー集。**剥奪期の証言コーパスがまるごと書籍化されている**最重要資料。要通読 → 台帳へ採録。

- **電王戦振り返り（２）示し始めた新しい価値観** — 遠山雄亮（将棋棋士）ブログ (2017-06-06)
  https://www.toyama-shogi.com/entry/2017/06/06/085632
  現役棋士による敗北直後の一人称論考。Ponanza の指し手を「新しい価値観」として受容し、敗れた当事者・佐藤天彦の言葉——「ちっぽけな一人の人間が焦りや苦しさを乗り越えて、観ている側が感動したり、あっと驚くような勝負をしたりする。それこそが人間の将棋の醍醐味」——を引用。**価値移転（成果物→人間ドラマ）の当事者証言**。

- **第2期電王戦結果 電王・Ponanzaが佐藤名人に勝利** — HEROZ (2017-04-03) / **将棋電王戦、佐藤名人がソフトに敗北** — 日本経済新聞 (2017-04-01)
  https://heroz.co.jp/release/2017/04/03shogi-2/ / https://www.nikkei.com/article/DGXLASDG01HCT_R00C17A4CC1000/
  年表の一次ソース。2017-04-01 第 1 局（71 手、タイトル保持者が公の場でソフトに初めて敗北）、2017-05-20 第 2 局（姫路城）で 2 連敗。電王戦は 6 年の歴史を終了。

- **藤井聡太が見る未来** — 藤井聡太 × 山中伸弥 対談 / 現代ビジネス (2023-10-15)
  https://gendai.media/articles/-/117775
  ネイティブ世代の一人称。AI を「序盤と中盤の形勢判断」の道具と語り、「コンピュータが一歩先を行っている」状況を dread なしに前提として受け入れる。AI 使用開始は奨励会三段の 2016 年頃（14 歳）。注意：記事タイトルの「AIを利用すれば人間はどんどん強くなれる」は本文中の一人称発言としては未確認（照合時の所見）。

- 未照合の次点資料（読む前に実在・内容確認すること）：渡辺明の「人間同士の勝負だから観る価値がある」旨の発言（『不屈の棋士』内とされる — 二次ソースの要約でのみ確認）、囲碁 AlphaGo 後の棋士証言、チェス post-Deep Blue の 20 年史。

## 8. 翻訳 — 第二の先行完走ドメイン（2026-08-16 追加）

将棋（競技）の外側、成果物の使用価値で回る**生産ドメイン**での剥奪期証言コーパス。理論上の位置付けは [concepts.md](concepts.md) 翻訳節、判定時期は 2028 年頃。

- **AI Killed My Job: Translators** — Brian Merchant / Blood in the Machine (2025-08-21)
  https://www.bloodinthemachine.com/p/ai-killed-my-job-translators
  翻訳者約 16 人の一人称証言集。『不屈の棋士』（2016）に構造的に対応する。**ほぼ全員が剥奪型で枯渇型ゼロ、しかもほぼ全員が今も仕事を愛している**——Katherine Kirby（伊英 14 年、"deeply love"、2025-06 から仕事ゼロ）、Julian Pintat（技術翻訳 15 年、post-editing を「憎むことになる」）、Laura Schultz（仏英 15 年超、2024 年以降に収入 60〜80% 減、別の芸術分野へ転向）、匿名の伊英翻訳者（「いっそ家の掃除で生計を立てた方がまし」）。年表の歪み：NMT の実用化（2016〜17）と経済的剥奪の本格化（2023〜）の間に 6〜8 年のラグ。既知の資料だったが reading-list 未収録だった。

## 探索の空白 — baseline 記録（2026-08-14 時点）

このフロンティアの中心仮説「一巡した人から順に、AI に頼むことが尽きる地点に着く」の定点観測の起点として、**まだ存在しないもの**を記録する。

- 英語圏: 「枯渇そのものの告白」に完全一致するのは Headmonk / Karson の 2 本のみ。Maganti は「欲望の在庫があった」側、Mahmud は思弁寄り
- 日本語圏: **「AI に頼むことがなくなった」「作りたいものが尽きた」型の一人称告白は発見できなかった**（起点エッセイを除く）。最も近いのは @IT コラム（情熱の喪失）と Qiita muu3（ポジティブな再定義）
- 空振りした検索クエリ（再現用）:
  - `note.com AI 「作りたいものがなくなった」 「頼むことがない」 虚無`
  - `「AIに聞くことがなくなった」 OR 「AIに頼むことがなくなった」 note はてな`
  - `AIで何でも作れるようになったのに「作りたいものがない」 エンジニア ブログ`
  - `Zenn note 「AIで作るのが虚しくなった」 OR 「作りたいものが思いつかない」 Claude Code 体験`
  - `はてな匿名ダイアリー AI 「作りたいものがない」 増田`
  - `Hacker News "I don't know what to build" OR "nothing left to build"`
  - 2026-08-17 追加（趣味制作者＝非生計依存層に絞った 2 本、いずれも creator economy の商業記事と burnout 一般論に流れた——**非生計依存層の証言は検索語で釣れる場所には無い**）: `hobbyist creators AI "lost interest" "nothing left to make" 2026 personal blog confession` / `Reddit 2026 "I have no ideas left" AI can build anything "don't want to build" burnout`
- 2026-08-19 再確認: 日本語圏の枯渇型ゼロ **6 日連続**。到達した新規は note.com/choo「個人開発をしてみたいけど、作りたいものがない人へ」のみで、一次 fetch の結果 **2024-11-19 公開・AI 言及なし・他人向け助言記事**（著者は既に脱して事業運営）——枯渇型ではないと判定、台帳未採録。クエリ：`個人開発 2026 「作ったけど公開していない」 AI 出すのが恥ずかしい 意味がない ブログ` / `2026 note Zenn 「作りたいものがない」 AI 何でも作れる 虚無 個人開発 一人称`。英語圏で「届かない・埋もれる」語彙（`2026 "no one sees it" OR "nobody notices" indie developer publishing AI flood attention "not worth posting" personal blog`）は Steam / インディー出版の商業記事に流れ一人称に届かず——08-18 の「釣れる語彙は公開・共有・見せる」は 1 回の追試で再現せず、弱く持ち直す
- 2026-08-18 再確認: 日本語圏の枯渇型ゼロ **5 日連続**。「AI で作ったと思われるのが嫌で公開しなくなった」型の検索は著作権・BAN 対策記事に流れ一人称に届かず——**日本語圏では公開の停止型も未出現**。英語圏は「公開・共有・見せる」の語彙で 3 本に到達（2026-08-17 の「非生計依存層は釣れない」は部分的に反故——層の不在でなくクエリが「枯渇」の語彙に寄りすぎていた）。反証方向 `2026 survey OR data hobbyist creators making more since AI "more motivated" personal projects increase evidence` → 該当なし（Kit / Adobe / Envato / Creative Boom はいずれも職業クリエイター対象）
- 2026-08-16〜17 再確認: 日本語圏の枯渇型は**ゼロのまま（4 日連続）**。新規に確認した 5 本（elliot_james / nishiken / yun_bow / ktg / tsuyuki）はいずれも枯渇型ではない（§3・§5）。日本語圏で実際に動いた防衛線は「何を作るかは人間に残る」（3 本目 tsuyuki）と「作れば誰かが使う」の否定（yun_bow）

この空白が埋まり始める時期・場所・語彙が、daily-research `desire` line の観測対象。
