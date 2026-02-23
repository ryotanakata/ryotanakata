```jsx
export const RyotaNakata = () => (
  <>
    <Frontend
      title="フロントエンド"
      years={6}
      languages={["JavaScript", "TypeScript", "React", "Next.js", "Liquid"]}
      markups={["HTML", "CSS", "Sass", "Scss"]}
      testing={["Jest", "Vitest"]}
    />
    <Backend
      title="バックエンド"
      years={3}
      languages={["PHP", "Laravel", "Ruby", "Ruby on Rails", "Node.js", "SQL"]}
      testing={["PHPUnit", "RSpec"]}
    />
    <Design
      title="デザイン"
      years={12}
      fields={["WEB", "UI/UX", "Graphic"]}
      tools={["Illustrator", "Photoshop", "Figma"]}
    />
    <Personal
      title="個人開発"
      projects={[
        { name: "tanshuku - シンプルな国産URL短縮サービス", url: "tanshuku.site" },
        { name: "b-graph - ビーモン会員のための、モチベーション管理ツール", url: "b-graph.me" },
        { name: "HTML5Nest - HTMLタグの入れ子を視覚化する開発支援ツール", url: "html5nest.com" },
        { name: "フォンクモーターサイクル - バイクカスタム店公式サイト", url: "fonkmotorcycle.jp" },
        { name: "ukka - オーダーメイドアクセサリー店ECサイト", url: "ukka.cc" },
      ]}
    />
  </>
);
```
