# GitHub Watchlist

注目しているGitHubリポジトリの台帳です。ChatGPTの定期調査から重複を除外し、新規リポジトリと重要な更新を反映します。

- 一意キー: `owner/repository`
- 表示列: リポジトリ / 分類 / 何ができるか / 注目ポイント / URL
- 重複Repoは行を増やさず、重要な変更がある場合のみ説明を更新
- 機械管理用の正本: `repositories.json`

最終移行日: 2026-09-19

| リポジトリ | 分類 | 何ができるか | 注目ポイント | URL |
|---|---|---|---|---|
| **xbtlin/ai-berkshire** | AI / 投資分析 | BuffettやMungerなどの投資手法をAIリサーチワークフローとして使う | 企業・業界・投資チェック向けのResearch SkillをClaude CodeやCodexから利用できる | https://github.com/xbtlin/ai-berkshire |
| **usestrix/strix** | AI / セキュリティ | AIエージェントによる自律的なペネトレーションテストを行う | 脆弱性探索からPoC検証まで自動化し、CI/CDへ組み込みやすい | https://github.com/usestrix/strix |
| **calesthio/OpenMontage** | AI / 動画生成 | リサーチ、台本、素材生成、編集まで動画制作をエージェント化する | 動画制作工程を複数のAgent Skillとツールで一気通貫に扱う | https://github.com/calesthio/OpenMontage |
| **Panniantong/Agent-Reach** | AI Agent / Tool | AIエージェントにWeb、YouTube、GitHub、Xなどへのアクセス能力を追加する | 既存CLIや取得ツールをまとめてAgentの能力レイヤーとして使える | https://github.com/Panniantong/Agent-Reach |
| **DeusData/codebase-memory-mcp** | Coding Agent / MCP | コードベースを解析して永続的な知識グラフを構築する | Coding Agentが毎回コード全体を読み直さず構造を把握しやすくする | https://github.com/DeusData/codebase-memory-mcp |
| **harry0703/MoneyPrinterTurbo** | AI / 動画生成 | AIを使って短尺動画の台本・素材・音声・編集などを自動化する | ShortsやSNS向け動画を一連のワークフローで生成できる | https://github.com/harry0703/MoneyPrinterTurbo |
| **tt-a1i/archify** | Coding Agent / 可視化 | コードや設計、処理フローを対話的な図に変換する | Coding Agentからアーキテクチャ図やシーケンス図を生成・保存できる | https://github.com/tt-a1i/archify |
| **THU-MAIC/OpenMAIC** | Multi-Agent / 教育 | 複数AIが先生役・生徒役に分かれて授業や学習対話を再現する | Multi-Agentでインタラクティブな学習環境を構築する | https://github.com/THU-MAIC/OpenMAIC |
| **K-Dense-AI/scientific-agent-skills** | AI Agent / 科学研究 | 生物・化学・医療などの調査・分析SkillをAI Agentへ追加する | 研究用途の多数のSkillと科学データベース連携をまとめている | https://github.com/K-Dense-AI/scientific-agent-skills |
| **jingyaogong/minimind** | LLM / 学習基盤 | 小型LLMをアーキテクチャから学習・推論までゼロから構築する | Pretrain、SFT、LoRA、RL、蒸留などを小規模実装で学べる | https://github.com/jingyaogong/minimind |
| **MadsLorentzen/ai-job-search** | AI Agent / 求職支援 | 求人探索、履歴書調整、応募管理、面接準備を支援する | 求職活動全体をローカルのAgentワークフローとしてまとめる | https://github.com/MadsLorentzen/ai-job-search |
| **tashfeenahmed/freellmapi** | LLM / API Router | 複数の無料LLMプロバイダを1つのOpenAI互換APIに束ねる | 無料枠の振り分けやFailoverを行い、各種Coding Agentから使いやすい | https://github.com/tashfeenahmed/freellmapi |
| **unclecode/crawl4ai** | AI / Web Crawling | WebページをAIやRAGが扱いやすいMarkdown・構造化データへ変換する | LLM向けデータ収集に特化したクローリングと抽出を自動化できる | https://github.com/unclecode/crawl4ai |
| **Osmantic/ODS** | Local AI / AI基盤 | PCをLLM、音声、RAG、画像生成などを動かすAIサーバーにする | 複数のローカルAI機能をセルフホスト環境へ統合する | https://github.com/Osmantic/ODS |
| **ChromeDevTools/chrome-devtools-mcp** | Coding Agent / MCP | Coding AgentからChrome DevToolsを操作・検査・デバッグする | 実ブラウザの動作確認、DOM調査、Performance解析をMCP経由で行える | https://github.com/ChromeDevTools/chrome-devtools-mcp |
| **PrimeIntellect-ai/prime-agent** | Coding Agent / 自律エージェント | 長時間のコーディングや自律タスクをStatefulに実行する | 自己改善型Agent Runtimeとして長時間タスクを扱う方向性が特徴 | https://github.com/PrimeIntellect-ai/prime-agent |
| **semantica-agi/semantica** | AI Agent / Memory・Knowledge Graph | Agentの知識・判断・コンテキストをグラフとして保存・推論する | Knowledge Graphや因果・provenanceを含むAgent Memory基盤 | https://github.com/semantica-agi/semantica |
| **addyosmani/agent-skills** | Coding Agent / Skills | 仕様化から実装、テスト、レビュー、リリースまでのSkillを提供する | ソフトウェア開発工程を再利用可能なAgent Skillとして体系化している | https://github.com/addyosmani/agent-skills |
| **cactus-compute/needle** | LLM / Edge AI | スマホ、ウェアラブル、ロボットなどで小型モデルのFunction Callingを行う | 超小型モデルをエッジ端末上のAgent用途へ使う設計が特徴 | https://github.com/cactus-compute/needle |
| **macro-inc/macro** | AI Agent / Workspace | Email、Chat、Docs、Tasks、CRMなどをAgentから横断利用する | Workspace全体を共有MemoryとしてAgentから扱える | https://github.com/macro-inc/macro |
| **google/skills** | AI Agent / Skills | Google製品・技術をAI Agentから扱うSkillを提供する | Google公式のAgent Skill群として製品連携の標準化を進める | https://github.com/google/skills |
| **paperclipai/paperclip** | Multi-Agent / Orchestration | 複数AI Agentの仕事、役割、コスト、目標を組織的に管理する | Agentを社員のように管理する上位のガバナンス・運用レイヤー | https://github.com/paperclipai/paperclip |
| **cloudflare/computer** | AI Agent / Computer Use | AI AgentへブラウザやGUIを含むコンピュータ操作環境を提供する | Agentが実際のコンピュータ操作を行うための実行環境を提供する | https://github.com/cloudflare/computer |
| **abhigyanpatwari/GitNexus** | Coding Agent / Code Intelligence | GitリポジトリからKnowledge Graphを生成してコードを探索する | Graph RAGでコード構造や関係を検索・理解しやすくする | https://github.com/abhigyanpatwari/GitNexus |
| **JetBrains/go-modern-guidelines** | Coding Agent / Skill | AI Coding Agentへ現代的なGo実装ガイドラインを与える | 言語固有の実装規約をSkillとして配布するJetBrainsの実例 | https://github.com/JetBrains/go-modern-guidelines |
| **workweave/router** | AI Agent / Model Router | Promptごとに適したLLMへ自動ルーティングする | OpenAI互換APIとして複数モデルのコスト・性能最適化を狙う | https://github.com/workweave/router |
| **magnitudedev/magnitude** | Local AI / Inference | PC性能に合うローカルLLMを選定・取得・推論サーバー化する | ローカル推論環境のモデル選択から実行までを自動化する | https://github.com/magnitudedev/magnitude |
| **pollen-robotics/microduck_rl** | Robotics / Reinforcement Learning | Microduckロボット向けにMuJoCo系RL学習と実機Policy実行を行う | 歩行や復帰など複数タスクをSim-to-Realまで試せる | https://github.com/pollen-robotics/microduck_rl |
| **google-research/timesfm** | AI / 時系列予測 | Foundation Modelで時系列データをZero-shot予測する | 時系列Foundation Modelの代表的OSSで、多変量や外生変数にも対応が進む | https://github.com/google-research/timesfm |
| **debpalash/VoiceStudio** | AI / 音声 | 音声クローン、音声生成、吹替、文字起こし等をローカルで行う | ローカル音声AI機能を統合した制作環境 | https://github.com/debpalash/VoiceStudio |
| **handsomestWei/patent-disclosure-skill** | AI Agent / 特許 | AI Agentで特許候補抽出、特許文書作成、読解、審査対応を支援する | 設計資料やコードから特許候補を抽出するSkill構成が参考になる | https://github.com/handsomestWei/patent-disclosure-skill |
| **tailscale/tailcat** | Network / Developer Tool | Tailscaleのデータプレーンを使ってマシン間通信を行う | WireGuardとDERPを利用したシンプルな通信ツールで仕組みの学習にも使える | https://github.com/tailscale/tailcat |
| **affaan-m/ECC** | Coding Agent / Agent Harness | Skills、Memory、Security、Workflow、OrchestrationをまとめてCoding Agent環境を構築する | 単一SkillではなくAgent開発環境全体を標準化するHarnessとして発展している | https://github.com/affaan-m/ECC |
| **Imbad0202/academic-research-skills** | AI Agent / Research | 調査、執筆、レビュー、修正まで研究工程を支援する | 文献探索や引用監査をSkill化しHuman-in-the-loopを重視する | https://github.com/Imbad0202/academic-research-skills |
| **bilawalsidhu/gods-eye-view** | AI / Spatial Intelligence | 衛星・航空などの実データを3D地球上で可視化・分析する | 3D GlobeとOSINT/地理空間分析を組み合わせたSpatial Intelligence基盤 | https://github.com/bilawalsidhu/gods-eye-view |
| **JustVugg/colibri** | LLM / Local Inference | 大型MoEモデルをCPU中心のローカル環境で実行する | Pure CとExpertストリーミングで大型MoEの省リソース実行を狙う | https://github.com/JustVugg/colibri |
| **alphaXiv/OpenResearch** | AI Agent / Research | 複数Research Agentを並列実行して調査結果を統合する | 研究課題をサブ問題へ分解し並列Agentで深掘りする | https://github.com/alphaXiv/OpenResearch |
| **XiaoDuoYa/codex-with-chatgpt** | Coding Agent / MCP | ChatGPTを計画役、Codexを実行役として連携する | 推論と実行を役割分担してMCP経由で接続する構成 | https://github.com/XiaoDuoYa/codex-with-chatgpt |
| **alibaba/open-code-review** | Coding Agent / Code Review | 静的解析とLLM Agentを組み合わせてコードレビューする | 決定論的ルールとLLMを併用しセキュリティや品質問題を検出する | https://github.com/alibaba/open-code-review |
| **tech-leads-club/agent-skills** | Coding Agent / Skills | 検証・安全性・バージョン管理を意識したAgent Skillを配布する | Skill Registry的な管理基盤として再利用性を高める | https://github.com/tech-leads-club/agent-skills |
| **tigerless-labs/agent-memory** | AI Agent / Memory | Claude CodeやCodexに共有の長期記憶を追加する | MarkdownをSource of Truthにして複数Agentが同じMemory Storeを共有する | https://github.com/tigerless-labs/agent-memory |
| **okf-memory/okf-agent-memory** | AI Agent / Memory | Git-nativeな永続メモリをCoding Agentへ提供する | Git、Markdown、BM25、MCPで外部DBなしのMemory管理を行う | https://github.com/okf-memory/okf-agent-memory |
| **unstablebuild/rune** | Coding Agent / Development Environment | 複数Coding Agentを扱うためのAgent前提開発環境を提供する | Terminal、Editor、Workspace管理をAgent Workflow向けに統合する | https://github.com/unstablebuild/rune |
| **2akouwu/reverify** | AI Agent / Verification | AI生成の主張を決定論的ツールとEvidenceで再検証する | LLMが提案しToolが判定する構成でHallucination抑制を狙う | https://github.com/2akouwu/reverify |
| **DietrichGebert/ponytail** | Coding Agent / Skills | AI Coding Agentへ最小実装・YAGNI・標準ライブラリ優先を促す | 過剰設計や不要な抽象化を抑える実用的なSkill群 | https://github.com/DietrichGebert/ponytail |
| **google/artemis** | AI Agent / Android Automation | 自然言語でAndroid端末やアプリ操作を自動化する | Coding Agentと接続し、操作実行やログ収集まで扱える | https://github.com/google/artemis |
| **EvoMap/AutoResearch** | AI Agent / Research | 研究アイデアから実験・評価・レビューまでを自動化する | 途中結果・コード・失敗理由を保持するStateful Research Agent | https://github.com/EvoMap/AutoResearch |
| **mksglu/context-mode** | Coding Agent / Context Management | MCPやツール出力を外部保持してコンテキスト消費を削減する | 必要な要約だけをモデルへ戻すことで長時間Agent作業を効率化する | https://github.com/mksglu/context-mode |
| **max-sixty/worktrunk** | Developer Tool / Agent Workflow | Git worktreeを簡単に管理し複数Coding Agentを並列実行する | Agentごとに作業ツリーを隔離して並列開発しやすくする | https://github.com/max-sixty/worktrunk |
| **earthtojake/text-to-cad** | AI Agent / CAD・Robotics | AgentからCAD、CAE、CAM、URDFなどを生成・編集する | 機械設計からロボット記述までAgent Skillで扱う点が特徴 | https://github.com/earthtojake/text-to-cad |
| **browser-use/video-use** | AI / 動画編集 | Coding Agentへ素材を渡して動画編集を自動化する | 字幕、カット、アニメーションなどを複数ツール・Agentで処理する | https://github.com/browser-use/video-use |
| **jihe520/MathModelAgent** | AI Agent / 数学・研究 | 数理モデリング、計算、可視化、文章化を自動化する | 数学研究・コンペ向けの一連のAgent Workflowを提供する | https://github.com/jihe520/MathModelAgent |
| **jordan-gibbs/hyperresearch** | AI Agent / Knowledge Base | Web調査結果を永続的な検索可能Wikiへ蓄積する | 単発Deep Researchではなく継続的な知識ベースとして残す設計 | https://github.com/jordan-gibbs/hyperresearch |
| **ayghri/i-have-adhd** | Coding Agent / Output Skill | Coding Agentの回答を結論・次の行動優先の短い形式へ整える | 能力追加ではなくAgentの出力スタイルをSkillとして制御する | https://github.com/ayghri/i-have-adhd |
| **mattpocock/skills** | Coding Agent / Skills | 仕様化、TDD、実装、レビュー、チケット分割など開発工程をSkill化する | 実開発フローそのものを再利用可能なSkillとして体系化している | https://github.com/mattpocock/skills |
