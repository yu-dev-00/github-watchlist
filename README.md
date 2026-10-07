# GitHub Watchlist

注目しているGitHubリポジトリの台帳です。ChatGPTの定期調査から重複を除外し、新規リポジトリと重要な更新を反映します。

- 一意キー: `owner/repository`
- 表示列: リポジトリ / 分類 / 何ができるか / 注目ポイント / URL
- 機械管理用の正本: `repositories.json`
- `watch`: 最近の注目度・開発活発度・新規性を追跡
- `evergreen`: 流行に左右されにくい長期参照用の定番
- 同じRepoは重複登録せず、重要な変更がある場合のみ説明を更新

最終更新日: 2026-10-08

## Trending / Watch

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
| **anthropics/knowledge-work-plugins** | AI Agent / Knowledge Work | 業務職種ごとのSkills、Connectors、Slash Commands、Sub-agentsをClaudeへ追加する | Product、Sales、Support、Legal、Finance、Dataなど11種の業務PluginをAnthropic公式が公開し、Claude Codeでも利用できる | https://github.com/anthropics/knowledge-work-plugins |
| **yynxxxxx/Codex-X** | Coding Agent / Codex Tool | Codex Desktop・CLIのPrompt、Provider、Session、Skills、MCP、設定をGUIで一元管理する | 複数Provider/APIや会話履歴、config.toml、Token使用量まで可視化するクロスプラットフォーム管理ツール | https://github.com/yynxxxxx/Codex-X |
| **cloudflare/security-audit-skill** | Coding Agent / Security Skill | Coding Agentに多段階のセキュリティ監査ワークフローを追加する | 偵察→Coverage管理→脆弱性探索→独立検証→機械可読なfinding→再検証までをSkillとして定式化している | https://github.com/cloudflare/security-audit-skill |
| **lahfir/agent-desktop** | AI Agent / Computer Use | AI AgentからOSのAccessibility Treeを使ってデスクトップアプリを操作する | 画像のピクセル推測ではなく安定したUI参照を使い、Rust CLI・C-ABI・構造化JSONでAgent操作を堅牢化する | https://github.com/lahfir/agent-desktop |
| **openai/tunnel-client** | AI Agent / MCP・Network | ローカルやプライベートネットワーク上のMCP ServerをChatGPTやCodexへ安全に接続する | MCP Serverを公開Internetへ露出せずSecure MCP Tunnel経由で接続でき、VM・Kubernetes・ローカルPCにも対応する | https://github.com/openai/tunnel-client |
| **vercel-labs/json-render** | AI / Generative UI | 自然言語から制約付きの動的UIを生成・レンダリングする | AIが定義済みComponent Catalog内だけでJSON UIを生成し、React・Vue・Svelte・React Native・3Dなどへ展開できる | https://github.com/vercel-labs/json-render |
| **withastro/flue** | AI Agent / Agent Framework | TypeScriptでSandbox、Skills、Tools、Subagents、永続実行を組み合わせた自律Agentを構築する | Agentを関数として定義し、ローカル/Remote SandboxとDurabilityを組み込めるAgent Harness Framework | https://github.com/withastro/flue |
| **docling-project/docling** | AI / Document AI | PDFやOffice文書、画像、音声などをLLM・RAG向けの構造化データへ変換する | 高度なPDFレイアウト・表・式・OCR解析に加え、Markdown/JSON出力、MCP、ローカル実行、動画・音声解析まで対応する | https://github.com/docling-project/docling |
| **kerpopule/hermes-jev-skills** | AI Agent / Routing・Skills | HermesやClaude Code、Codexへ高速なモデルルーティング、メモリ選別、Skill選択、Computer/Browser Useの判断支援を追加する | TypeSafeのJevを使い、文章生成ではなく選択・スコアリングなどの小さな判断を高速・低コストに分離する。Hermes向けPluginに加えて汎用SKILL.mdとしても利用できる | https://github.com/kerpopule/hermes-jev-skills |
| **typesafe-ai/skills** | AI Agent / Skills・Decision | TypeSafeのSystem Oneモデルを使い、ルーティング、ランキング、抽出、検証などの型付き判断をAgentワークフローへ組み込む | Jevなどのモデルを自然言語生成ではなくtyped judgment/probabilityとして使い、LLMのPrompt→Parse処理を小さな決定プリミティブへ置き換える設計 | https://github.com/typesafe-ai/skills |
| **OpenHands/OpenHands** | Coding Agent / Autonomous Development | AI Agentがコード理解・編集・コマンド実行・デバッグなどのソフトウェア開発タスクを自律的に進める | Agent SDK、CLI、ローカルGUIを備え、ローカル実行から多数Agentのスケールまで扱える代表的なオープンソース開発Agent基盤 | https://github.com/OpenHands/OpenHands |
| **TauricResearch/TradingAgents** | Multi-Agent / 金融・投資 | 複数のLLM Agentが市場・ニュース・ファンダメンタルズを分析し、議論して投資判断を組み立てる | LangGraphベースでAnalyst、Researcher、Trader、Portfolio Managerなどを役割分担し、チェックポイントやバックテストも備える金融Multi-Agentフレームワーク | https://github.com/TauricResearch/TradingAgents |
| **danny-avila/LibreChat** | AI / Multi-Model Chat Platform | OpenAI、Anthropic、Googleなど複数AIプロバイダを1つのセルフホストUIから利用する | マルチモデル切替に加え、Agents、MCP、Artifacts、Code Interpreter、検索、マルチユーザー認証まで統合したオープンソースAIチャット基盤 | https://github.com/danny-avila/LibreChat |
| **CopilotKit/OpenBot** | AI Agent / Computer Use・Workspace | AI Agentごとに専用ブラウザ、ファイル領域、ツールを持つ実行用コンピュータを割り当て、Webやソフト操作を行わせる | 各Botに独立したComputerを与え、操作前のPolicy判定と操作後のAuditを通す設計。AG-UI Agentを自社インフラ上のAI Coworkerとして動かせる | https://github.com/CopilotKit/OpenBot |
| **vectorize-io/hindsight** | AI Agent / Memory | AI Agentに長期記憶を追加し、事実・経験・観察・メンタルモデルを蓄積・想起・内省する | 会話履歴の検索だけでなく継続的に学習するMemory Systemを志向し、MCPやCoding Agentにも統合できる | https://github.com/vectorize-io/hindsight |
| **mvschwarz/openrig** | Multi-Agent / Coding Harness | Claude CodeやCodexなど複数Coding Agentをチームとして定義し、役割分担・連携・レビューを一つのRigで運用する | 永続セッション、TUI、キュー、スナップショット・復旧などを持ち、複数Agentを継続的な開発チームとして管理できる | https://github.com/mvschwarz/openrig |
| **dream-num/univer** | AI Agent / Office Automation | Spreadsheet・Docs・SlidesなどのOfficeコンテンツを構造化APIから生成・編集し、AI Agentの作業対象にする | ブラウザとNode.jsで同じAPIを利用でき、Agentが内容やレイアウトを検証しながらOffice文書を扱える | https://github.com/dream-num/univer |
| **superdesigndev/treg** | AI Agent / Tool Router | 多数の外部APIやチーム内のCLI・Skillを一つの接続先からAgentに提供する | ツール探索・呼出し・接続設定をサーバー側へ集約し、チームのAgentから共通利用できる。セルフホストにも対応する | https://github.com/superdesigndev/treg |
| **google/ax** | AI Agent / Orchestration Runtime | Agentタスク・Workspace・Modelを宣言的に定義し、隔離Sandbox上で大規模に実行・監視する | Kubernetesに似た操作感でTask・Workspace・Modelを管理し、Git・MCP・Skillsの事前配線やsuspend/resume、sshを備える | https://github.com/google/ax |
| **Tencent/BrowserSkill** | AI Agent / Browser Automation | Claude CodeやCodexなどのAgentからChrome・Edgeを操作し、閲覧・フォーム入力・デバッグ・スクリーンショットなどを行う | CLIとブラウザ拡張を組み合わせ、専用Agent Window、明示的なタブ借用、操作履歴・監査を提供する | https://github.com/Tencent/BrowserSkill |
| **NVIDIA/SkillSpector** | AI Agent / Skill Security | Agent Skillをインストール前に解析し、安全性やSupply Chain上のリスクを検査する | Git・URL・ZIP・ローカルSkillを静的解析と任意のLLM解析で検査し、JSON・Markdown・SARIFやMCP ServerでCIへ組み込める | https://github.com/NVIDIA/SkillSpector |
| **rohitg00/ai-engineering-from-scratch** | AI / 学習・教材 | AI Engineeringを基礎からLLM、MCP、Agent Engineering、Agent Skillsまで手を動かして学ぶ | 500超のLessonと再利用可能なPrompt・Skill・Agent・MCP成果物を含み、日本語入口やCoding Agent向けTutor Skillも用意されている | https://github.com/rohitg00/ai-engineering-from-scratch |
| **stablyai/orca** | Coding Agent / Orchestration・IDE | Codex、Claude Code、OpenCodeなど複数のCLI Coding Agentを並列worktreeで実行・比較・レビューする | Agentごとの独立Git worktree、モバイルからの監視・指示、GitHub/Linear連携、SSH先での実行、AI Diffレビュー、Computer Useまで統合したAgent前提の開発環境 | https://github.com/stablyai/orca |
| **VectifyAI/PageIndex** | AI / RAG・Document Retrieval | PDFや長文書を階層ツリーとして索引化し、ベクトル検索ではなくLLMの推論で関連箇所をたどって取得する | Vector DBや固定Chunkingを使わず、文書構造とコンテキストを保ったまま検索できるReasoning-based RAG。長い技術文書・規格書・論文・契約書などに向く | https://github.com/VectifyAI/PageIndex |
| **google/mantis** | Coding Agent / Security・Vulnerability Research | AI Agentでコードベースの脅威モデル作成、脆弱性仮説生成、検証、再現、修正、再検証までを多段階で実行する | Google公開のセキュリティ研究向けAgent Harness。履歴分析、Semantic Index、重複排除、Severity校正、脆弱性チェーン探索まで含む。隔離環境での利用を強く前提とする | https://github.com/google/mantis |
| **Tencent/WeKnora** | AI / Knowledge Platform・RAG | 企業文書を取り込み、RAG検索、Multi-step Agent、Wiki/Knowledge Graph、MCP、長期Memoryまで一つの知識基盤で扱う | PDFやOffice文書、複数データソースを統合し、RAG・Agent・Wikiを同じKnowledge Base上で利用できる。Self-host、Ollama、BrowserSkill、Sandbox、RBACにも対応する | https://github.com/Tencent/WeKnora |
| **tester-army/e2e** | AI / E2E Testing | 自然言語でWeb・モバイルアプリの操作目標を記述し、Agentが実際に操作してE2Eテストを実行する | Agentが成功した操作を記録し、次回以降はアプリが変わるまでモデル呼び出しなしで再生できる。Playwright系WebとiOS/Androidの両方に対応する | https://github.com/tester-army/e2e |
| **pbakaus/impeccable** | Coding Agent / UI・Design Skill | Coding AgentへUI設計・レビュー・改善・ブラウザ反復のためのデザインSkillとコマンド群を追加する | 24コマンドと61個の決定論的検出ルールを持ち、AI生成UIにありがちな見た目の癖を抑えつつ、PRODUCT.mdやDESIGN.mdで設計文脈を継続利用する | https://github.com/pbakaus/impeccable |
| **thedotmack/claude-mem** | AI Agent / Memory・Context | Agentの作業内容をセッション横断で圧縮・保存し、後続セッションへ関連コンテキストを再注入する | Claude Code向けに始まった永続Memory基盤で、現在はCodex・Gemini・Copilot・OpenCodeなど複数Agentとの併用を意識している | https://github.com/thedotmack/claude-mem |
| **pingdotgg/t3code** | Coding Agent / Control Surface | ローカルPC上のClaude Code、Codex、Cursor、OpenCodeなど複数Coding AgentをWeb・Desktop・Mobile UIから操作する | 既存CLI Agentを置き換えずに外側から制御するAgent Harnessの操作面で、スマホからの遠隔操作にも対応する | https://github.com/pingdotgg/t3code |
| **openai/plugins** | Coding Agent / Plugins | Codex向けPluginの公式サンプルと、Skill・MCP・Agent・Command・Hookを組み合わせるPlugin構成例を提供する | OpenAI公式のPlugin Catalogで、Figma、Notion、Web/iOS/macOS開発、Expo、Remotion、Google Slidesなど実用的な統合例をまとめている | https://github.com/openai/plugins |
| **NousResearch/hermes-agent** | AI Agent / Self-Improving Agent | 経験からSkillを生成・改善し、長期Memory、サブAgent、Scheduler、複数メッセージング経路を持つ自律Agentを構築・実行する | 自己改善ループとAgent-curated Memoryを内蔵し、ローカル・Docker・SSH・Serverlessなど複数実行基盤へ展開できる | https://github.com/NousResearch/hermes-agent |
| **garrytan/gstack** | Coding Agent / Development Workflow | Coding Agentへ企画・設計・実装レビュー・QA・セキュリティ・リリースなど役割別の開発Skillを追加する | CEO、Eng Manager、Designer、Reviewer、QA、Security、Releaseなどの役割を分け、ソフトウェア開発工程全体をSkillベースで運用する | https://github.com/garrytan/gstack |
| **antirez/ds4** | Local AI / Inference | DeepSeek V4系やGLM 5系など一部の大型Open-weightモデルをMac、CUDA、ROCmなどのローカル環境で高速推論する | 汎用ランタイムではなく対象モデルを絞って最適化し、SSD Streaming、複数GPU、RDMA、Pipeline/Tensor Parallelまで扱う | https://github.com/antirez/ds4 |
| **heygen-com/hyperframes** | AI / Agentic Video | HTML・CSS・Media・Seekable Animationを使い、Agentから決定論的なMP4動画を生成する | Claude Code、Codex、Cursor、Gemini CLI向けSkillを備え、Web表現をそのまま動画生成ワークフローへ使える | https://github.com/heygen-com/hyperframes |
| **cathrynlavery/diagram-design** | Coding Agent / Diagram・Visualization | Claude CodeやCodexからアーキテクチャ図、フロー、Sequence、ER、Ganttなど多数の編集品質の図をHTML+SVGで生成する | Mermaid依存を避け、静的HTMLを基本に必要ならMotionも追加できる。既存のdraw.io・Mermaid・Excalidraw図の再描画にも対応する | https://github.com/cathrynlavery/diagram-design |
| **ruvnet/ruflo** | Multi-Agent / Agent Harness | Claude CodeやCodexへ複数AgentのSwarm、長期Memory、Sandbox、学習ループ、Federationを追加して協調実行する | 100以上の専門Agentを束ねるMeta-Harnessで、タスクルーティング・自己学習・クロスマシン連携まで一つの実行層として扱う | https://github.com/ruvnet/ruflo |
| **openclaw/openclaw** | AI Agent / Personal Assistant | ローカル環境を中心にAIアシスタントを構築し、複数モデルやツールを組み合わせて使う | 個人向けAI Agentをセルフホストして拡張する基盤として注目。ローカル実行や外部モデル連携の選択肢が広い | https://github.com/openclaw/openclaw |
| **ollama/ollama** | Local AI / Inference | LLMやVLMなどのOpen-weightモデルをローカルPCで簡単に取得・実行する | ローカルAI実行基盤の事実上の定番の一つで、各種Agent・UI・RAG基盤との接続点として重要 | https://github.com/ollama/ollama |
| **langchain-ai/langchain** | AI Agent / Framework | LLMアプリ、Agent、Tool連携、RAGなどを構築するためのフレームワークを提供する | 成熟したエコシステムを持ち、Agent開発の比較基準として引き続き重要 | https://github.com/langchain-ai/langchain |
| **n8n-io/n8n** | Automation / AI Workflow | 多数のサービスを接続し、AIを含む業務ワークフローをノーコード/ローコードで自動化する | 通常の自動化とAI Agentを同じWorkflow上で組み合わせやすく、実運用用途で強い | https://github.com/n8n-io/n8n |
| **langgenius/dify** | AI / Application Platform | LLMアプリ、RAG、Agent、Workflow、モデル管理を統合して構築・運用する | AIアプリを試作から運用まで一つの基盤で扱える代表的なOSSプラットフォーム | https://github.com/langgenius/dify |
| **langflow-ai/langflow** | AI Agent / Visual Workflow | LLM・Agent・RAG・Tool連携をビジュアルなフローとして設計・実行する | Agent WorkflowをGUIで構成・確認でき、実験とプロトタイプ作成に向く | https://github.com/langflow-ai/langflow |
| **mem0ai/mem0** | AI Agent / Memory | AI AgentやLLMアプリへユーザー・会話・タスクの長期Memoryを追加する | Agent Memoryの代表的OSSで、Memory層をモデル本体から分離する設計の比較対象として重要 | https://github.com/mem0ai/mem0 |
| **browser-use/browser-use** | AI Agent / Browser Automation | AI AgentがWebブラウザを認識・操作してWebタスクを自動実行する | Browser Agent分野の代表的プロジェクトで、Web操作をAgentの実行能力として組み込む用途に向く | https://github.com/browser-use/browser-use |
| **microsoft/markitdown** | AI / Document Processing | PDF・Office・画像など各種ファイルをLLMが扱いやすいMarkdownへ変換する | RAGやAgentへの文書入力前処理としてシンプルに使いやすいMicrosoft製ツール | https://github.com/microsoft/markitdown |
| **open-webui/open-webui** | Local AI / Chat Platform | ローカルモデルや各種AI APIをセルフホストのWeb UIから利用・管理する | Ollamaなどとの組み合わせでローカルAI環境のフロントエンドとして広く利用されている | https://github.com/open-webui/open-webui |
| **browserbase/stagehand** | AI Agent / Browser Automation | コードによるブラウザ操作とAIによる柔軟なWeb操作を組み合わせて自動化する | 決定論的操作とAgent操作の中間を狙う設計で、壊れにくいBrowser Automation基盤として注目 | https://github.com/browserbase/stagehand |
| **firecrawl/firecrawl** | AI / Web Data | Webサイトをクロールし、LLMやRAGで使いやすいMarkdown・構造化データへ変換する | Webデータ取得をAI向けにまとめた代表的基盤で、検索・抽出・Agent連携まで用途が広い | https://github.com/firecrawl/firecrawl |
| **vllm-project/vllm** | LLM / Inference | LLMを高スループット・高効率でGPU推論・Servingする | OpenAI互換Servingや量子化・分散推論などを備え、大規模モデル運用の中心的OSS | https://github.com/vllm-project/vllm |
| **ggml-org/llama.cpp** | LLM / Local Inference | LLMをCPU・GPUを含む幅広い環境で軽量にローカル推論する | GGUFや量子化を中心とした省メモリ推論エコシステムの基盤で、ローカルAIでは特に重要 | https://github.com/ggml-org/llama.cpp |
| **run-llama/llama_index** | AI / RAG・Data Framework | LLMアプリから文書・DB・APIなどの外部データを検索・利用するためのRAG基盤を構築する | Data/RAG層の代表的フレームワークで、Agentと外部知識を結ぶ設計比較に有用 | https://github.com/run-llama/llama_index |
| **infiniflow/ragflow** | AI / RAG Platform | 文書解析・検索・RAG・Agentを統合した知識ベースを構築する | 文書理解を重視したRAG基盤として、企業文書や複雑なPDFの活用に向く | https://github.com/infiniflow/ragflow |
| **supermemoryai/supermemory** | AI Agent / Memory・Context | AI Agentやアプリへ長期MemoryとContext Retrievalを提供する | Agentが必要な記憶を継続利用するContext Engineとして、Memory分野の動向を見る上で重要 | https://github.com/supermemoryai/supermemory |
| **ComposioHQ/awesome-claude-skills** | AI Agent / Skills Catalog | Claude Codeを中心としたAgent SkillやPluginの事例・リソースを一覧化する | Skillエコシステム全体を俯瞰するための索引として有用で、他のCoding Agentへ応用できる事例も多い | https://github.com/ComposioHQ/awesome-claude-skills |
| **comfyanonymous/ComfyUI** | AI / Image・Video Workflow | 画像・動画生成モデルをノードベースのWorkflowとして組み合わせて実行する | 生成AIの新モデル・新手法をローカルで試す共通基盤として現在も重要度が高い | https://github.com/comfyanonymous/ComfyUI |

## Evergreen

| リポジトリ | 分類 | 何ができるか | 注目ポイント | URL |
|---|---|---|---|---|
| **public-apis/public-apis** | Developer Resource / API | 無料・公開APIをカテゴリ別に探す | 試作や学習で外部APIを探す際の定番カタログ | https://github.com/public-apis/public-apis |
| **codecrafters-io/build-your-own-x** | Learning / Build From Scratch | DB、OS、Git、コンテナなどを自作して仕組みを学ぶ教材を探す | 内部構造を実装から理解したいときの長期的な定番資料 | https://github.com/codecrafters-io/build-your-own-x |
| **kamranahmedse/developer-roadmap** | Learning / Roadmap | 分野別の学習ロードマップと必要技術を確認する | 新しい技術分野へ入るときの全体像把握に便利 | https://github.com/kamranahmedse/developer-roadmap |
| **EbookFoundation/free-programming-books** | Learning / Books | 多数の言語・技術分野の無料教材や書籍を探す | プログラミング学習資料の巨大な長期保存カタログ | https://github.com/EbookFoundation/free-programming-books |
| **donnemartin/system-design-primer** | Software Architecture / System Design | 大規模システム設計の基本概念・設計問題・面接対策を学ぶ | System Designの基礎を体系的に確認できる定番資料 | https://github.com/donnemartin/system-design-primer |
| **jwasham/coding-interview-university** | Learning / CS・Interview | CS基礎、アルゴリズム、データ構造を体系的に学習する | コンピュータサイエンス基礎を長期計画で学ぶ定番カリキュラム | https://github.com/jwasham/coding-interview-university |
| **jlevy/the-art-of-command-line** | Developer Tool / Command Line | Unix/Linuxのコマンドライン操作を効率よく学ぶ | シェル操作・テキスト処理・デバッグの実践知を簡潔にまとめた定番資料 | https://github.com/jlevy/the-art-of-command-line |
| **practical-tutorials/project-based-learning** | Learning / Project Based | 実際のアプリやシステムを作りながら各技術を学ぶ教材を探す | 手を動かして学ぶプロジェクト型教材の長期的な索引 | https://github.com/practical-tutorials/project-based-learning |
| **getify/You-Dont-Know-JS** | Learning / JavaScript | JavaScriptの言語仕様・挙動を深く理解する | JavaScriptの内部挙動まで掘り下げる定番シリーズ | https://github.com/getify/You-Dont-Know-JS |
| **trimstray/the-book-of-secret-knowledge** | Developer Resource / Knowledge | CLI、ネットワーク、セキュリティ、DevOpsなどの実践的Tipsを参照する | 幅広い開発・運用知識を横断的にまとめたリファレンス | https://github.com/trimstray/the-book-of-secret-knowledge |
| **yangshun/tech-interview-handbook** | Learning / Interview | ソフトウェアエンジニア面接のコーディング・設計・行動面接を準備する | 技術面接準備の体系的な定番ガイド | https://github.com/yangshun/tech-interview-handbook |
| **awesome-selfhosted/awesome-selfhosted** | Developer Resource / Self-hosted | 自分でホストできるOSSサービスを用途別に探す | セルフホスト可能なソフトウェアを探す際の代表的カタログ | https://github.com/awesome-selfhosted/awesome-selfhosted |
| **trekhleb/javascript-algorithms** | Learning / Algorithms | JavaScript実装付きでアルゴリズムとデータ構造を学ぶ | 実装を読みながらアルゴリズムを確認できる定番教材 | https://github.com/trekhleb/javascript-algorithms |
| **Chalarangelo/30-seconds-of-code** | Developer Resource / Snippets | JavaScript・CSS・Reactなどの短い実装例やパターンを参照する | 小さな実装パターンを素早く確認するための長期的リファレンス | https://github.com/Chalarangelo/30-seconds-of-code |
| **github/gitignore** | Developer Tool / Git | 言語・IDE・環境別の.gitignoreテンプレートを利用する | GitHub公式の定番テンプレート集で、新規プロジェクト作成時に継続的に使える | https://github.com/github/gitignore |
| **freeCodeCamp/freeCodeCamp** | Learning / Programming | Web開発やプログラミングを実践課題で学ぶ | 大規模な無料学習カリキュラムとして長期的な参照価値が高い | https://github.com/freeCodeCamp/freeCodeCamp |
