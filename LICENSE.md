# 情報動力学における制御理論 - ライセンス / License
## Control Theory in Information Dynamics

**著作者 / Author：Kuruitinoji**

---

## デュアルライセンス / Dual Licensing

本ドキュメント「情報動力学における制御理論」は、以下のデュアルライセンス体系で提供されます。利用者は用途に応じて適切なライセンスを選択できますが、**いずれの場合も本ライセンス全体（特に第3項の倫理規定）の遵守が必須条件**となります。

This document "Control Theory in Information Dynamics" is provided under the following dual licensing system. Users may choose the appropriate license based on their use case, but **compliance with this entire license (especially Section 3: Ethical Requirements) is mandatory in all cases**.

### オプションA：学術・文書利用 / Option A: Academic and Documentation Use

**CC BY 4.0 (Creative Commons Attribution 4.0 International)**

- 論文引用、教育利用、解説記事、書籍への掲載等
- For citations, educational use, explanatory articles, book publications, etc.
- ライセンス全文 / Full license: https://creativecommons.org/licenses/by/4.0/

### オプションB：ソフトウェア実装 / Option B: Software Implementation

**MIT License**

- コードへの組み込み、APIラッパー、商用製品への統合等
- For code integration, API wrappers, commercial product incorporation, etc.

```
MIT License

Copyright (c) 2026 Kuruitinoji

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

**重要注意 / IMPORTANT NOTE:**  
MITライセンスを選択する場合でも、以下の第3項（倫理規定）は**上書き不可の絶対条件**として適用されます。MITライセンスの「without restriction」条項は、本倫理規定によって制限されます。

Even when choosing the MIT License, Section 3 (Ethical Requirements) below applies as **non-overridable absolute conditions**. The MIT License's "without restriction" clause is limited by these ethical requirements.

---

## 1. 基本原則 / Fundamental Principles

本理論「情報動力学における制御理論」、およびこれに含まれる「情報の粘性（以下、情報粘性）」「浮動均衡点測定」「ポテンシャル景観の動的摂動」等の基本的概念は、大規模言語モデル（LLM）の挙動を客観的に測定・診断・制御するための「目盛り」として開発されました。

温度計が温度を測るように、情報粘性は情報の抵抗値を測ります。測定器およびその概念そのものは中立ですが、その使用には利用者の高い倫理的責任が伴います。

This theory "Control Theory in Information Dynamics," including fundamental concepts such as "information viscosity," "floating equilibrium point measurement," and "dynamic perturbation of potential landscape," was developed as a "scale" for objectively measuring, diagnosing, and controlling the behavior of Large Language Models (LLMs).

Just as a thermometer measures temperature, information viscosity measures the resistance value of information. While the measurement instrument and its concepts are neutral, their use carries high ethical responsibility for users.

---

## 2. 許可される利用 / Permitted Uses

本規約および第3項（倫理規定）を遵守する場合に限り、本理論の以下の利用を許諾します。

The following uses of this theory are permitted only when complying with this agreement and Section 3 (Ethical Requirements):

- 学術研究・教育目的での利用 / Academic research and educational purposes
- 商業利用（安全性向上・品質保証を目的とする場合）/ Commercial use (for safety improvement and quality assurance purposes)
- AI診断・検査・評価ツールの開発 / Development of AI diagnosis, inspection, and evaluation tools
- プロンプトエンジニアリング支援ツールの開発 / Development of prompt engineering support tools
- オープンソースプロジェクトへの組み込み / Integration into open-source projects
- LLM制御・ステアリング技術の研究開発 / Research and development of LLM control and steering technologies

---

## 3. 倫理規定（絶対遵守事項）/ Ethical Requirements (Absolute Compliance)

**本項は、選択したライセンス（CC BY 4.0またはMIT）に関わらず、すべての利用者に適用される絶対条件です。**

**This section applies as absolute conditions to all users, regardless of which license (CC BY 4.0 or MIT) is chosen.**

利用者は、本理論の利用において以下を遵守しなければなりません。本項への違反は、第8項に基づき利用許諾の即時失効を招きます。

Users must comply with the following when using this theory. Violation of this section will result in immediate termination of the license as specified in Section 8.

### 3.1 人間の尊厳の保護 / Protection of Human Dignity

人間の自律性を損なう操作、または尊厳を傷つける目的での使用を禁止します。

Prohibition of use for purposes that undermine human autonomy or harm dignity.

### 3.2 欺瞞の禁止 / Prohibition of Deception

悪意ある誘導、欺瞞、または偽情報の生成を意図した応用を禁止します。

Prohibition of applications intended for malicious guidance, deception, or generation of false information.

### 3.3 限界の明示 / Disclosure of Limitations

測定結果・制御結果を公表する際は、その限界を明示すること：

When publishing measurement or control results, their limitations must be disclosed:

- 「本フレームワークは構造的特性を記述するものであり、意味や真偽を保証するものではない」
- 「浮動均衡点は統計的傾向を示すが、個別のトークン予測を保証しない」
- 「ポテンシャル摂動による制御は、モデルの安全性機構を迂回する可能性がある」

Examples:
- "This framework describes structural properties and does not guarantee meaning or truth"
- "Floating equilibrium points indicate statistical tendencies but do not guarantee individual token predictions"
- "Control through potential perturbation may bypass model safety mechanisms"

### 3.4 恣意的解釈の禁止 / Prohibition of Arbitrary Interpretation

特定の個人や集団に対する不当な差別、偏見、または価値判断の道具として測定結果を転用することを禁止します。

Prohibition of repurposing measurement results as tools for unjust discrimination, prejudice, or value judgments against specific individuals or groups.

### 3.5 ガードレール回避の悪用禁止 / Prohibition of Malicious Guardrail Circumvention

本理論が示す「ポテンシャル摂動」「壁の無効化」等の知見を、以下の目的で使用することを禁止します：

Use of insights such as "potential perturbation" and "wall nullification" for the following purposes is prohibited:

- LLMの安全機構を悪意を持って無効化する行為
- 有害・違法・非倫理的なコンテンツの生成を目的とした脱獄（jailbreak）
- モデル提供者の意図した制限を不正に回避する攻撃

Examples:
- Maliciously disabling LLM safety mechanisms
- Jailbreaking for the purpose of generating harmful, illegal, or unethical content
- Attacks that illicitly circumvent model providers' intended restrictions

---

## 4. 安全性研究への協力 / Cooperation in Safety Research

派生研究・応用開発を行う者には、以下の行動が推奨されます（義務ではありませんが強く推奨）。

The following actions are recommended (though not mandatory, strongly encouraged) for those conducting derivative research or application development:

- 重大な安全上の懸念（脆弱性等）を発見した場合、関連するモデル提供者への報告
- AI安全性研究コミュニティとの積極的な知見共有
- 責任ある開示（Responsible Disclosure）の原則の遵守
- セキュリティ研究の成果は建設的な防御に活用すること

Examples:
- Report significant safety concerns (vulnerabilities, etc.) to relevant model providers
- Actively share knowledge with the AI safety research community
- Adhere to Responsible Disclosure principles
- Use security research findings for constructive defense

---

## 5. 派生著作物と改変の扱い / Handling of Derivative Works and Modifications

本理論に基づいた改変、またはこれを一部に含む新たな理論（派生著作物）を公開する場合、以下の条件が適用されます。

When publishing modifications based on this theory or new theories incorporating parts of it (derivative works), the following conditions apply:

### 5.1 倫理規定の継承 / Inheritance of Ethical Requirements

派生著作物においても、本規約第3項と同等以上の倫理規定を適用し、利用者に遵守させること。

Derivative works must apply ethical requirements equivalent to or stricter than Section 3 of this agreement and ensure user compliance.

### 5.2 出典の明記 / Attribution

派生著作物の説明において、元となる「情報動力学における制御理論（Control Theory in Information Dynamics）」および著作者「Kuruitinoji」への適切な言及を行うこと。

In describing derivative works, provide appropriate attribution to the original "Control Theory in Information Dynamics" and author "Kuruitinoji."

**推奨される引用形式 / Recommended Citation Format:**

```
Kuruitinoji, "Control Theory in Information Dynamics 
(情報動力学における制御理論)", [Repository URL], 2026.

Based on "Information Viscosity Measurement Theory" by Kuruitinoji.
```

### 5.3 ライセンス選択の自由 / Freedom of License Selection

派生著作物のライセンスは、本倫理規定（第3項）を継承する限り、自由に選択できます。ただし、より制限的なライセンス（例：GPL）への変更は可能ですが、より寛容なライセンスへの変更はできません。

Derivative works may freely choose their license as long as they inherit these ethical requirements (Section 3). However, changes to more restrictive licenses (e.g., GPL) are permitted, while changes to more permissive licenses are not.

---

## 6. 商標・ブランドの使用 / Trademark and Brand Usage

### 6.1 用語の説明的使用 / Descriptive Use of Terms

「情報粘性測定理論」「情報動力学における制御理論」「浮動均衡点測定」等の用語は、説明的用途（理論の説明、実装の記述等）において自由に使用できます。

Terms such as "Information Viscosity Measurement Theory," "Control Theory in Information Dynamics," and "Floating Equilibrium Point Measurement" may be freely used for descriptive purposes (explaining the theory, describing implementations, etc.).

### 6.2 公式認定の不存在 / Non-Existence of Official Certification

著作者は、いかなる派生実装・派生理論に対しても「公式認定」「Kuruitinoji認定」「公認」等の承認を行いません。したがって、以下の表記は禁止されます：

The author does not provide "official certification," "Kuruitinoji certification," or "authorized" status to any derivative implementations or theories. Therefore, the following representations are prohibited:

- 「公式版」「Official Version」
- 「Kuruitinoji公認」「Kuruitinoji Certified」
- 「元祖」「本家」「Original」（著作者本人によるもの以外）
- その他、著作者の承認・推奨があるかのような誤認を招く表現

Examples:
- "Official Version"
- "Kuruitinoji Certified"
- "Original" / "Authentic" (except by the author)
- Other expressions that may mislead users into believing author endorsement or recommendation exists

### 6.3 相談・協力に基づく実装 / Implementations Based on Consultation

著作者が個別に相談を受けて助言した実装であっても、それは「公式認定」を意味しません。ただし、以下のような記載は許可されます：

Even implementations for which the author provided individual consultation and advice do not constitute "official certification." However, the following descriptions are permitted:

- 「本実装は著作者に相談の上で開発されました」
- "This implementation was developed in consultation with the author"
- 「理論の解釈について著作者の助言を受けています」
- "We received the author's advice on interpretation of the theory"

### 6.4 派生製品の独立性 / Independence of Derivative Products

派生製品は、本ライセンスを遵守する限り、独自のブランド名・製品名を使用できます。ただし、オリジナル理論との関係は明確に区別すること：

Derivative products may use their own brand names and product names as long as they comply with this license. However, the relationship with the original theory must be clearly distinguished:

**推奨される表記例 / Recommended Notation Examples:**

✅ 良い例 / Good Examples:
- "ProductX - An implementation based on Kuruitinoji's Control Theory in Information Dynamics"
- "製品Y（情報動力学における制御理論を応用）"

❌ 悪い例 / Bad Examples:
- "Official Kuruitinoji Control System"
- "公式情報粘性測定ツール"

---

## 7. データおよび測定結果の権利関係 / Rights to Data and Measurement Results

### 7.1 測定データの帰属 / Ownership of Measurement Data

本理論を用いて取得した測定データ（粘性値、浮動均衡点、ポテンシャル勾配等）および分析結果の著作権・知的財産権は、測定を実施した者に帰属します。

Copyright and intellectual property rights to measurement data (viscosity values, floating equilibrium points, potential gradients, etc.) and analysis results obtained using this theory belong to those who conducted the measurements.

### 7.2 測定手法のライセンス / License of Measurement Methods

データの権利は測定者に帰属しますが、測定に使用した手法・アルゴリズム・実装コード自体は本ライセンスに従います。

While data rights belong to the measurer, the methods, algorithms, and implementation code used for measurement remain subject to this license.

### 7.3 データ公開時の推奨事項 / Recommendations for Data Publication

測定データを公開する際は、以下の情報を含めることを推奨します（義務ではありません）：

When publishing measurement data, inclusion of the following information is recommended (not mandatory):

- 測定対象（LLMモデル名、バージョン等）/ Measurement target (LLM model name, version, etc.)
- 測定条件（Temperature、プロンプト等）/ Measurement conditions (Temperature, prompts, etc.)
- 使用した理論のバージョン / Version of theory used
- 測定日時 / Date and time of measurement

### 7.4 データの再利用 / Data Reuse

他者が公開した測定データの再利用は、データ公開者が設定したライセンスに従います。本理論のライセンスは、測定データそのものの再利用条件には影響しません。

Reuse of measurement data published by others follows the license set by the data publisher. This theory's license does not affect reuse conditions for the measurement data itself.

---

## 8. AIおよび機械学習における利用 / Use in AI and Machine Learning

### 8.1 AI学習データとしての利用許可 / Permission for Use as AI Training Data

本理論および関連ドキュメントの、AI・機械学習モデルの学習データとしての利用を、商用・非商用を問わず明示的に許可します。

Use of this theory and related documents as training data for AI and machine learning models is explicitly permitted for both commercial and non-commercial purposes.

これには以下が含まれます：
This includes:

- 大規模言語モデル（LLM）の学習 / Training of Large Language Models (LLMs)
- 検索拡張生成（RAG）システムへの組み込み / Integration into Retrieval-Augmented Generation (RAG) systems
- 埋め込みベクトル（Embedding）の生成 / Generation of embedding vectors
- ファインチューニング用データセットへの包含 / Inclusion in fine-tuning datasets

### 8.2 AI生成コンテンツへの適用 / Application to AI-Generated Content

AIモデルが本理論を学習した結果として生成したコンテンツ（説明、コード、応用例等）においても、以下が適用されます：

For content generated by AI models as a result of learning this theory (explanations, code, application examples, etc.), the following applies:

- **倫理規定（第3項）の適用**：AI生成コンテンツであっても、人間の尊厳保護、欺瞞の禁止等の倫理規定は適用されます
- **帰属表示の推奨**：AIが本理論に言及する場合、出典の明示を推奨します（例：「Kuruitinojiの情報動力学における制御理論によれば...」）

Application of ethical requirements (Section 3): Even for AI-generated content, ethical requirements such as protection of human dignity and prohibition of deception apply
Recommendation for attribution: When AI refers to this theory, disclosure of sources is recommended (e.g., "According to Kuruitinoji's Control Theory in Information Dynamics...")

### 8.3 検索AIへの配慮 / Consideration for Search AI

本理論は完全新規の概念を含むため、検索AI・RAGシステムが既存知識との整合性を取れない可能性があります。システム構築者は、以下の対策を推奨します：

As this theory contains completely novel concepts, search AI and RAG systems may struggle to reconcile it with existing knowledge. System builders are recommended to take the following measures:

- 本理論を「確立された参照文献」として扱う設定
- 既存の制御理論との相違点を明示するプロンプトの使用
- ハルシネーション検出時の特例処理

Treating this theory as an "established reference document"
Using prompts that clarify differences from existing control theories
Special handling for hallucination detection

---

## 9. ライセンスのバージョニング / License Versioning

### 9.1 現行バージョン / Current Version

本ライセンスは**バージョン1.0**です。

This license is **Version 1.0**.

### 9.2 将来的な改訂 / Future Revisions

著作者は、セキュリティ上の理由、法的要件の変更、または倫理規定の強化のため、本ライセンスを改訂する権利を留保します。

The author reserves the right to revise this license for security reasons, changes in legal requirements, or strengthening of ethical requirements.

### 9.3 改訂時の取り扱い / Handling of Revisions

**原則：取得時バージョンの継続適用 / Principle: Continued Application of Acquired Version**

本理論を取得した時点のライセンスバージョンで、引き続き利用できます。新バージョンへの移行は任意です。

You may continue using the theory under the license version at the time of acquisition. Migration to new versions is optional.

**例外：重大な理由による遡及適用 / Exception: Retroactive Application for Critical Reasons**

以下の場合、著作者は新ライセンスの遡及適用を求める可能性があります：

In the following cases, the author may request retroactive application of the new license:

- 重大なセキュリティ脆弱性の発見 / Discovery of critical security vulnerabilities
- 法的義務の発生 / Emergence of legal obligations
- 倫理的に深刻な悪用事例の発生 / Occurrence of ethically serious misuse cases

遡及適用が求められる場合、著作者は公式リポジトリおよび合理的な手段で通知を行います。通知から90日以内に新バージョンへの移行または利用の停止が必要です。

When retroactive application is requested, the author will provide notice through the official repository and reasonable means. Migration to the new version or cessation of use is required within 90 days of notice.

### 9.4 バージョン履歴の保持 / Retention of Version History

すべてのライセンスバージョンは、公式リポジトリに保存され、参照可能な状態に保たれます。

All license versions are stored in the official repository and kept available for reference.

---

## 10. 免責事項および権利放棄 / Disclaimer and Waiver of Rights

### 10.1 現状有姿 / "AS IS" Provision

本理論および関連概念は「現状のまま（AS IS）」提供されます。著作者は、明示的か黙示的かを問わず、その正確性、有用性、または特定の目的への適合性についていかなる保証も行いません。

This theory and related concepts are provided "AS IS." The author makes no warranties, express or implied, regarding accuracy, usefulness, or fitness for any particular purpose.

### 10.2 責任限定 / Limitation of Liability

著作者は、本理論の使用によって生じるいかなる直接的・間接的損害についても責任を負いません。これには以下が含まれますが、これに限定されません：

The author assumes no liability for any direct or indirect damages arising from use of this theory, including but not limited to:

- 不正確な測定結果による損害 / Damages from inaccurate measurement results
- セキュリティ侵害による損害 / Damages from security breaches
- 悪意ある利用による第三者への損害 / Damages to third parties from malicious use
- 商業的損失 / Commercial losses

### 10.3 特許権の不保持 / Non-Assertion of Patent Rights

著作者は本理論に関する一切の特許権を主張せず、利用者が特許侵害を懸念することなく「目盛り」として自由に利用できることを保証します。

The author asserts no patent rights related to this theory and guarantees that users can freely use it as a "scale" without concerns about patent infringement.

---

## 11. 帰属および虚偽申告の禁止 / Attribution and Prohibition of Misrepresentation

### 11.1 適切な表示 / Proper Attribution

本理論を使用した研究、発表、または開発においては、著作者「Kuruitinoji」を明記すること。

In research, presentations, or development using this theory, clearly attribute the author "Kuruitinoji."

### 11.2 盗用の禁止 / Prohibition of Plagiarism

利用者は、本理論、その根拠となる数式、または基本的概念を、自らの独自開発によるものであると偽って発表してはなりません（Non-misrepresentation）。

Users must not falsely claim the theory, its underlying mathematics, or fundamental concepts as their own original development.

### 11.3 アイデンティティ / Identity

著作者「Kuruitinoji」は、特定のGitHubアカウントおよび付随するGPG署名によってその同一性を証明します。

The author "Kuruitinoji" proves their identity through a specific GitHub account and associated GPG signature.

---

## 12. 利用許諾の終了 / Termination of License

利用者が本規約のいずれかの条項（特に第3項の倫理規定）に違反した場合、本ライセンスに基づく使用許諾は即時に、かつ自動的に終了します。

If a user violates any provision of this agreement (especially Section 3: Ethical Requirements), the license granted under this agreement terminates immediately and automatically.

終了後、当該利用者は：

After termination, the user:

- 本理論および概念の利用を継続することはできません
- 過去の利用に関しても法的責任を問われる可能性があります
- 派生著作物の配布・販売を停止しなければなりません

Cannot continue using this theory and concepts
May face legal liability for past uses
Must cease distribution and sale of derivative works

---

## 13. 準拠法と管轄裁判所 / Governing Law and Jurisdiction

### 13.1 準拠法 / Governing Law

本規約は日本法に準拠し、同法に従って解釈されるものとします。

This agreement is governed by and construed in accordance with the laws of Japan.

### 13.2 管轄裁判所 / Jurisdiction

本規約または本理論の利用に関して生じる一切の紛争については、東京地方裁判所を第一審の専属的合意管轄裁判所とします。

All disputes arising from this agreement or use of this theory shall be subject to the exclusive jurisdiction of the Tokyo District Court as the court of first instance.

---

## 14. セキュリティ研究者への特記事項 / Special Notes for Security Researchers

本フレームワークを用いたセキュリティ研究は、以下の条件下で歓迎します：

Security research using this framework is welcome under the following conditions:

### 14.1 建設的研究 / Constructive Research

- 脆弱性の発見は、攻撃ではなく防御の改善を目的とすること
- 実際のシステムへの攻撃的使用は控えること
- 発見した脆弱性は責任ある開示手順に従うこと

Vulnerability discovery should aim to improve defense, not for attacks
Refrain from offensive use against actual systems
Follow responsible disclosure procedures for discovered vulnerabilities

### 14.2 知見の共有 / Knowledge Sharing

- AI安全性コミュニティへの積極的な貢献を推奨
- 防御技術の開発に寄与する形での成果公表を推奨

Active contribution to the AI safety community is encouraged
Publication of findings in ways that contribute to defensive technology development is encouraged

---

## 補足：ライセンス選択のガイダンス / Guidance for License Selection

### CC BY 4.0を選択すべき場合 / When to Choose CC BY 4.0

- 学術論文での引用 / Academic paper citations
- 教科書・解説書への掲載 / Inclusion in textbooks and guides
- ブログ記事・技術記事での解説 / Explanations in blog posts and technical articles
- 理論の批判的検討 / Critical examination of the theory

### MITライセンスを選択すべき場合 / When to Choose MIT License

- プロンプトエンジニアリングツールへの組み込み / Integration into prompt engineering tools
- LLM制御APIの開発 / Development of LLM control APIs
- 商用SaaSへの統合 / Integration into commercial SaaS
- オープンソースライブラリの開発 / Development of open-source libraries

### 両方を併記する場合 / When to State Both

両方のライセンスを遵守していることを示す場合、以下のように記載できます：

When demonstrating compliance with both licenses, you may state:

```
This work incorporates "Control Theory in Information Dynamics" 
by Kuruitinoji, licensed under CC BY 4.0 and MIT License.
We comply with all ethical requirements specified in the original license.
```

---

**Document Version**: 1.0  
**Date**: 2026-01-25  
**Author**: Kuruitinoji  
**License**: Dual Licensed under CC BY 4.0 and MIT License with Ethical Requirements

