# AI News Blog

AI 동향 자동 발행 사이트. [ai_news_agent](https://github.com/altjs4510/ai_news_agent) 가 매주 결과 마크다운을 이 레포의 `content/posts/` 에 push하면, GitHub Actions가 [Quartz v4](https://quartz.jzhao.xyz/) 로 빌드해 GitHub Pages에 배포합니다.

게시 URL: https://altjs4510.github.io/ai_news_blog

## 구조

```
content/
  index.md           # 첫 페이지
  posts/             # 날짜별 발행물 (agent가 자동 작성)
    YYYYMMDD/
      reddit_insights.md
      summary.md
      ...
```

## 로컬 미리보기

```bash
npm install
npx quartz build --serve
```

빌드 도구 출처: [jackyzha0/quartz](https://github.com/jackyzha0/quartz) (MIT).
