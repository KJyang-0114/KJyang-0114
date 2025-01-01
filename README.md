```typescript
class KJyang {
  name: string = 'KJyang';
  title: string = '遊戲玩家 | 網站開發者';
  website: string = 'https://github.com/kjyang-0114/KJyang-website';
  
  constructor() {
    console.log('Welcome to my GitHub! 👋');
  }
  
  getSkills(): Record<string, string[]> {
    return {
      frontend: ['Vue 3', 'Vite', 'JavaScript', 'CSS3', 'HTML5'],
      backend: ['Node.js', 'Express'],
      tools: ['Git', 'VS Code', 'Font Awesome'],
      design: ['Vuestic UI', 'Responsive Design']
    };
  }
  
  getProjects(): Array<object> {
    return [
      {
        name: '個人網站',
        description: '使用 Vue 3 + Vite 構建的個人網站',
        features: [
          '🎮 遊戲精華時刻展示',
          '👨‍💻 個人介紹頁面',
          '📝 留言板功能',
          '🎨 現代化深色主題設計'
        ]
      }
    ];
  }
  
  getContacts(): Record<string, string> {
    return {
      github: 'kjyang-0114',
      instagram: '@kjyang_0114',
      discord: 'https://discord.gg/sZbn6Dw3Bx'
    };
  }
}

// 初始化
const me = new KJyang();
```

### 🎯 最新專案

```javascript
const currentProject = {
  name: '個人網站',
  stack: ['Vue 3', 'Vite', 'Node.js', 'Express'],
  features: {
    videoGallery: '支援 Google Drive 視頻播放',
    design: '響應式布局 + 深色主題',
    interaction: '即時留言功能'
  }
};
```

### 📊 GitHub 統計

![GitHub 統計](https://github-readme-stats.vercel.app/api?username=kjyang-0114&show_icons=true&theme=dark)

### 🤝 聯繫我

```python
def contact_me():
    return {
        "GitHub": "kjyang-0114",
        "Instagram": "@kjyang_0114",
        "Discord": "https://discord.gg/sZbn6Dw3Bx"
    }
```

---
⭐️ From [KJyang](https://github.com/kjyang-0114)
