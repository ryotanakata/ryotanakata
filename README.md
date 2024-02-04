```jsx
export const RyotaNakata = () => (
  <>
    <Frontend
      title="フロントエンド"
      years={5}
      languages={["JavaScript", "React", "Next.js", "Liquid"]}
      markups={["HTML", "CSS", "Sass", "Scss"]}
    />
    <Backend
      title="バックエンド"
      years={3}
      languages={["PHP", "Laravel", "Node.js"]}
      databases={["MySQL", "MariaDB"]}
    />
    <Design
      title="デザイン"
      years={12}
      fields={["WEB", "UI/UX", "Graphic"]}
      tools={["Illustrator", "Photoshop", "Figma"]}
    />
    // TODO: スキルをもっと追加
    <Others title="その他" direction videoEdit logicalThink />
  </>
);
```
