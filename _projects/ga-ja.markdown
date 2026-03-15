---
layout: project
title: "アニメーション動画作成プラットフォーム"
date: 1999-05-01 00:00:00
project-date: "2014 - 2018"
description: "新規ユーザーとパワーユーザーの双方に対応するインタラクションパターンの再設計——学習曲線の削減と、製品・チームのスケールに合わせた一貫した機能開発の実現。"
teaser-image: /assets/img/ga-teaser.png
screens: /assets/img/ga-screens.png
tags: [情報アーキテクチャ, インタラクションパターン, ユーザーリサーチ]
lang: ja
---

<!-- Hero Section -->
<div class="full-width-section" style="background-color: #EDEFF2;">
  <div class="container">
    <div class="d-flex justify-content-between align-items-baseline">
      <h1>{{ page.title }}</h1>
      <a href="/projects/ga.html" class="lang-switch-link">English</a>
    </div>
    <p>{{ page.description }}</p>
    <div class="py-4">
      <img src="/assets/img/ga-screens.png" class="img-fluid rounded" alt="Vyond Studioでのプロップ編集">
      <figcaption class="figure-caption text-center mt-2">Vyond Studioでのプロップ編集</figcaption>
    </div>
    <hr class="project-meta-rule">
    <div class="project-meta-grid">
      <div>
        <div class="meta-label">役割</div>
        <p class="meta-value">シニアUXデザイナー</p>
      </div>
      <div>
        <div class="meta-label">チーム</div>
        <p class="meta-value">デザイン、エンジニアリング、プロダクト</p>
      </div>
      <div>
        <div class="meta-label">期間</div>
        <p class="meta-value">2014 – 2018</p>
      </div>
      <div>
        <div class="meta-label">スキル</div>
        <p class="meta-value meta-skills">情報アーキテクチャ · インタラクションパターン · ユーザーリサーチ</p>
      </div>
    </div>
  </div>
</div>

<!-- Overview Section -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">概要</h3>
    <p>Vyondは新しい技術スタックへの移行と、製品・チームの急速な拡大が重なる時期を迎えていました。ベータリリース直前のユーザーテストで重大な問題が明らかになりました——新規ユーザーは基本タスクを完了できず、既存のパワーユーザーは使い慣れた機能を見つけられない状態でした。</p>
    <p>根本原因は個々の機能ではなく、情報アーキテクチャにありました。複数のデザイナーが全体的な視点なく各機能を担当した結果、製品は断片化し、一貫性を欠いていました。</p>
    <p>デザインチーム（UIおよびUX）とエンジニアリングと協力し、3つのユーザータイプ（初めて動画を作る初心者、作業効率を求めるパワーユーザー、ブランドアセットを管理する意思決定者）に対応できるインタラクションパターンを確立しました。</p>
    <p>これらのパターンは学習曲線を短縮し、パワーユーザーの効率を向上させ、私が退職した後も数年にわたって使い続けられています。</p>
  </div>
</div>

<!-- Background Section -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">背景</h3>
    <p>私がVyondの香港オフィスに入社した2014年、同社は製品市場フィット（PMF）に近づいていました。チームは精鋭——約30名の社員の中にデザイナーは3名——で、香港、台湾、サンフランシスコのメンバーと高い連携で働いていました。</p>
    <p>年間で社員数が倍増する中、スケールに耐えるデザイン基盤の構築に貢献しました：</p>
    <ul>
      <li><strong>デザインプロセス：</strong>製品・デザイン・エンジニアリング間の連携を改善する構造化されたワークフロー</li>
      <li><strong>ユーザーテスト文化：</strong>定期的なテストにより摩擦点を発見し、チーム全体でユーザー中心の文化を醸成</li>
      <li><strong>オンボーディング改善：</strong>ユーザージャーニーのマッピングによりチャーンを削減し、定着率を向上</li>
      <li><strong>インタラクションパターン：</strong>一貫性と開発速度向上のための再利用可能なパターンの文書化</li>
    </ul>
  </div>
</div>

<!-- Problem -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">課題</h3>
    <p>ベータテストで重大なユーザビリティの問題が明らかになりました：</p>
    <ul>
      <li>新規ユーザーは基本的なタスク（初めての動画作成）を完了できなかった</li>
      <li>パワーユーザーは機能を見つけられても、アプリ全体でパターンが統一されておらず、操作を覚え直す必要があり認知負荷が高く、ワークフローが遅くなっていた</li>
      <li>製品全体が断片化して感じられた</li>
    </ul>
    <p>根本原因は、デザイナーたちが統一した情報アーキテクチャなく、それぞれ並行して機能を開発していたことでした。各機能は独立して機能していましたが、全体として見ると一貫性のない体験になっていました。</p>
    <p>テスト結果を確認したリーダーシップは、リリース前にこの問題を修正することに合意しました。</p>
    <img src="/assets/img/ga-asset-panel-before.png" class="img-fluid rounded mt-4" alt="再設計前のアセットパネル">
    <p class="figure-caption text-center mt-2">再設計前のアセットパネル——各機能がそれぞれ独自の一貫性のないインタラクションパターンを持っていた</p>
  </div>
</div>

<!-- Approach Section -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">アプローチ</h3>
    <p>デザインチームとエンジニアリングと共に、以下のニーズに対応できるパターンを設計しました：</p>
    <ol>
      <li>初心者がコア機能を発見・使用しやすくする</li>
      <li>パワーユーザーにワークフロー効率を提供する（彼らは動画の作り方を知っている——スピードとスケールが重要）</li>
    </ol>
    <p>設計対象のユーザータイプを特定しました：</p>
    <ul>
      <li>新規ユーザー：初めて動画を作成する、ガイダンスが必要</li>
      <li>プロダクトチャンピオン：多数の動画を制作するパワーユーザー、効率性が重要</li>
    </ul>
    <p>解決策は「ツールボックス」と呼ぶ、製品全体に一貫して適用するプログレッシブディスクロージャーパターンでした：</p>
    <ul>
      <li>クイックアクセス（ユーザーのブックマーク）</li>
      <li>最近使用したもの（リピートユーザーへの高速アクセス）</li>
      <li>カテゴリ（発見のための整理されたブラウジング）</li>
      <li>カスタム（ブランドアセットまたはカスタム）</li>
    </ul>
    <p>このひとつのパターンが、異なる深さで複数のユーザータイプに対応——初心者には明確な出発点、パワーユーザーには最近使用したものへの高速アクセス、エンタープライズチームにはブランドコントロールを提供しました。</p>
    <img src="/assets/img/journey1.png" class="img-fluid rounded mt-4" alt="ツールボックスパターン">
    <p class="figure-caption text-center mt-2">ツールボックスパターン——すべてのユーザータイプに対応するプログレッシブディスクロージャーシステム</p>
  </div>
</div>

<!-- Outcome Section -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">成果</h3>
    <p>新しいパターンを実装し、追加テストを実施した結果：</p>
    <ul>
      <li>新規ユーザーが初めての動画を完成できるようになった（以前は苦労または失敗していた）</li>
      <li>パワーユーザーが認知負荷なく機能を見つけられるようになった——アプリ全体での一貫したパターン</li>
      <li>エンタープライズチームがブランドアセットの使用を管理できるようになった</li>
    </ul>
    <p>ユーザビリティ指標を超えて、パターンはチームのスケールを可能にしました：</p>
    <ul>
      <li>文書化された再利用可能なパターンにより、デザインとエンジニアリングの作業速度が向上</li>
      <li>ナビゲーションを毎回ゼロから考えることなく、一貫した新機能の構築が可能に</li>
      <li>パターンは私が退職した後も数年にわたって使い続けられている</li>
    </ul>
    <p>再設計により学習曲線が短縮し、サブスクリプションが増加しました。</p>
  </div>
</div>

<!-- Example Section -->
<div class="full-width-section" style="background-color: #EDEFF2; padding: 4rem 0;">
  <div class="container">
    <div style="padding:62.12% 0 0 0;position:relative;">
      <iframe src="https://player.vimeo.com/video/676490224?h=a49b27c683&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Color Properties"></iframe>
    </div>
    <p class="figure-caption text-center mt-2">デザインパターンの実際——ユーザーが色を閲覧、適用、保存、再利用する流れ（26秒）。</p>
  </div>
</div>

<!-- Reflections Section -->
<div class="full-width-section" style="background-color: #fff; padding: 4rem 0;">
  <div class="container">
    <h3 class="page-label mb-3">振り返り</h3>
    <p>機能のリリースに追われがちです——特に動きの速いスタートアップでは。しかし、一歩引いて実際に全体がどのように機能しているかをテストし理解しなければ、誰のためにもならない断片化した製品を作り続けることになります。</p>
    <p>このプロジェクトは、開発し続けるプレッシャーの中でも、プロトタイピングとテストのための時間を確保することの大切さを改めて気づかせてくれました。</p>
  </div>
</div>
