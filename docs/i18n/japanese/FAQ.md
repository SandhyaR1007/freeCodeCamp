### GitHub とオープンソースは初めてです。 どこから始めればいいですか？

[「オープンソースに貢献する方法ガイド」](https://github.com/freeCodeCamp/how-to-contribute-to-open-source) をご覧ください。 これは、初心者にも優しいプロジェクトのための包括的な参照です。 オープンソースへの貢献に関するヒントを多く含んでいます。

### コードベースに貢献するために知っておくべきことは何ですか？

freeCodeCamp は、モダンな JavaScript スタック上で動作します。 コードベースで貢献することにご興味がある場合は、JavaScript および Node.js、MongoDB、OAuth 2.0、React、Gatsby、Webpack のようなテクノロジーに精通している必要があります。

### freeCodeCamp のリソースを翻訳できますか？

はい。翻訳プラットフォームで有効になっている 30 以上の言語を貢献できます。

ユーザーが行った翻訳が既に存在する言語もあります。 freeCodeCamp を世界の主要な言語にローカライズしていく予定です。 You can read all about this in our [announcement here](https://www.freecodecamp.org/news/help-translate-freecodecamp-language/).

If you are interested in contributing to translations please make sure you [read this guide](how-to-translate-files.md) first.

### freeCodeCamp ニュースの記事や、freeCodeCamp YouTube チャンネルの動画に貢献することはできますか？

はい。ニュースブログや YouTube チャンネルに貢献することができます。

freeCodeCamp ニュースの記事を書くことにご興味がありましたら、[執筆ガイド](https://www.freecodecamp.org/news/how-to-write-for-freecodecamp/) をご覧ください。 より力強い、より効果的な記事を書くために、[スタイルガイド](https://www.freecodecamp.org/news/developer-news-style-guide/) をお読みください。

YouTube チャンネル用の動画講座を作成するには、[YouTube チャンネルガイド](https://www.freecodecamp.org/news/how-to-contribute-to-the-freecodecamp-community-youtube-channel-b86bce4c865/) をお読みください。

### 新しいバグはどのように報告すればいいですか？

If you think you've found a bug, first read the ["How to Report a Bug"](https://www.freecodecamp.org/news/how-to-report-a-bug-to-freecodecamp/) article and follow its instructions.

新しいバグだという確信がある場合は、GitHub Issue を作成してください。 バグを再現できるように、できるだけ多くの情報を含めるようにしてください。 これをサポートするために、事前に定義された Issue 用テンプレートがあります。

これらの GitHub Issue は、コードベース関連の問題や議論のためのものであり、コードを学習するための助けを得るためのものではありません。 疑わしい場合は GitHub Issue を作成する前に、[フォーラム](https://forum.freecodecamp.org) で支援を求めます。

### セキュリティ問題はどのように報告すればいいですか？

セキュリティ問題のために GitHub Issue を作成しないでください。 代わりに、[こちらのセキュリティポリシー](https://contribute.freecodecamp.org/#/security)に従ってください。

### 私は学生です。 単位取得を目的として、機能に関して貢献することはできますか？

はい。 ただし、大学での要件となるような時間軸や書類に関与することはできませんのでご注意ください。 私たちはボランティア開発者から多くのプルリクエストやコードの貢献を受けており、皆さんの時間と努力を尊重しています。 すべての貢献者に対して敬意を払っているため、学校関連だからと言って PR 特別優先事項を与えることはありません。

これを念頭におき、事前にご自身で計画を立てたうえで、コードの貢献に取り組むようお願いいたします。

### GitHub Issue にタグ付けされた様々なラベルはどのような意味ですか？

コードメンテナーは、優先度、重大度、およびその他の要因に基づいて、Issue とプルリクエストを [トリアージ](https://en.wikipedia.org/wiki/Software_bug#Bug_management) します。 [ラベルの意味の用語集](https://github.com/freecodecamp/freecodecamp/labels) をご覧ください。

### Issue の作業に貢献するには、何から始めたらいいですか？

貢献可能な作業にどのようなものがあるか把握するため、まずは [**`help wanted`**](https://github.com/freeCodeCamp/freeCodeCamp/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22) または [**`first timers only`**](https://github.com/freeCodeCamp/freeCodeCamp/issues?q=is%3Aopen+is%3Aissue+label%3A%22first+timers+only%22) のラベルが付いた Issue を確認してください。

> [!TIP] **`help wanted`** の Issue は誰でも作業が可能であり、作業前に許可を求める必要はありません。 ただし、 **`first timers only`** ラベルが付けられた Issue は、初めて freeCodeCamp コードベースに貢献する人用の特別な Issue です。

### タイプミスを見つけました。 プルリクエストを行う前に Issue を作成すべきですか？

タイプミスや文言変更の場合、Issue を作成せずに、直接プルリクエストをオープンして構いません。 些細な変更であっても、プルリクエストの説明には詳しい情報を記載してください。皆様の貢献を理解しレビューする際に役立ちます。

コードベースやカリキュラムの大きな側面について議論したい場合は、Issue を作成してください。

### Issue を割り当て (アサイン) してもらうにはどうすればいいですか？

通常、長期的なコントリビューター以外には Issue を割り当てません。 その代わりに、以下の方針に従い、すべての人対して公平であるようにしています。

1. Issue に対処する最初のプルリクエストをマージする可能性が最も高いです。
2. 複数のコントリビューターが同じ Issue に対してプルリクエストを同時にオープンした場合、 最善の対処をするプルリクエストを優先します。 考慮事項:
   - テストを含めましたか？
   - Did you catch all use cases?
   - すべてのテストに合格し、すべてがローカルで動作することを確認しましたか？
3. 最後に、推奨ガイドラインに従ったプルリクエストを優先します。
   - プルリクエストのチェックリストに従って確認しましたか？
   - プルリクエストに意味のあるタイトルを付けましたか？

### freeCodeCamp のモデレーターになりたいです。 何から始めればいいですか？

コミュニティモデレーターは、私たちのヒーローです。 モデレーターの自発的な貢献により、freeCodeCamp は安全で快適なコミュニティになっています。

何よりもまず、コミュニティの積極的な参加者となり、[行動規範](https://www.freecodecamp.org/japanese/news/code-of-conduct/) を強制するだけでなくその規範に従って行動する必要があります。

いくつかのプラットフォームで推奨されるパスを以下に示します。

- **Discord／チャット**  のモデレーターになるには、チャットに積極的に参加し、発生する可能性のある潜在的な衝突への対処方法を学ぶとともに実践しながら、他の人と積極的に関わってください。
- To be a **Forum** moderator, similar to a chat moderator, have an active presence and engage with other forum posters, supporting others in their learning journey, and even giving feedback when asked. 詳細については、[サブフォーラムリーダーハンドブック](https://forum.freecodecamp.org/t/the-subforum-leader-handbook/326326) をご覧ください。
- **GitHub** モデレーターになるには、提起された GitHub Issue の処理を手伝います。それらが有効であるかどうかを確認し、(理想的には) Issue に対するソリューションを提案して、他の人 (または自分自身) が対応できる状態にします。

つまり、他の人に敬意を払ってください。 人々は世界中から集まっています。 これを念頭に置いて、励ましの言葉または応援する言葉を使用し、異文化間のコミュニケーションを意識してください。

**一定期間、着実に** 上記を実行し、仲間のモデレーターがあなたを推薦した場合に、スタッフから連絡が来て、モデレーターチームに加わることができます。 オープンソース作業はボランティアであり、私たちの時間は限られています。 皆様も、おそらく同じだと思います。 したがって、24 時間年中無休でコミュニティに参加するのではなく、**着実に** 取り組んでいただきたいです。

モデレーターの責任と期待に関する包括的なリストは、[モデレーターハンドブック](moderator-handbook.md) をご覧ください。

### このドキュメントに記載されていない問題で困っています。

**以下に、お気軽にお問い合わせください。**

- [コミュニティフォーラム](https://forum.freecodecamp.org/c/contributors) の `Contributors` カテゴリ
- [チャットサーバーの ](https://discord.gg/PRyKn3Vbay) `#Contributors` チャンネル

取り組みたいトピックに貢献するお手伝いをさせていただけることを嬉しく思います。 関連する問題のスレッドについて質問をいただいた場合は、喜んで明確にします。 新しい質問を投稿する前に、必ずその質問を検索してください。

礼儀正しく忍耐強い対応を、お願いいたします。 このコミュニティは主にボランティアによって運営されていることをご理解ください。

### その他の支援

スタック、コードベースのアーキテクチャー、翻訳などについて質問がある場合は、[フォーラムの](https://forum.freecodecamp.org/g/team) スタッフチームまでお気軽にご連絡ください。

**`dev[at]freecodecamp.org` にて、開発者スタッフにメールでお問い合わせいただけます。**
