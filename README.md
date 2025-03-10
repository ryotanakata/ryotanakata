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
      languages={["PHP", "Laravel", "Node.js"]}
      databases={["MySQL", "MariaDB"]}
      testing={["PHPUnit"]}
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
        { name: "b-graph - ビーモン会員ための、ワークアウト記録サービス", url: "b-graph.me" },
        { name: "HTML5Nest - マークアップ支援ツール", url: "html5nest.com" },
        { name: "フォンクモーターサイクル - 公式サイト", url: "fonkmotorcycle.jp" },
        { name: "ukka - ECサイト", url: "ukka.cc" },
      ]}
    />
  </>
);
```
