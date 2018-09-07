dfs 全称是 [Depth First Search](https://en.wikipedia.org/wiki/Depth-first_search)。

是一种图的遍历算法。

所谓深度优先。就是说每次都尝试向更深的节点走。
如果没有更深的节点了，就回到上一层的下一个节点继续刚才的过程。

## 实现

伪代码：

```
dfs(u) {
  visited[u] = true
  for each edge(u, v) {
    if (!visited[v]) {
      dfs(v)
    }
  }
}
```

C++：

```c++
void dfs(int u) {
  vis[u] = 1;
  for (int i = head[u]; i; i = e[i].x) {
    // 这里用到的是链式前向星来存图
    if (!vis[ e[i].t ]) {
      dfs(v);
    }
  }
}
```

时间复杂度 $O(n + m)$

空间复杂度 $O(n)$ （vis 数组和递归栈）

## [在树 / 图上 dfs](/graph/traverse)
