# MCP 簡介

Model Context Protocol（MCP，模型上下文協議）是一套規範，旨在讓應用程式能夠以標準化方式回覆大型語言模型（LLM）所需的上下文資訊，提升 LLM 的準確性、降低幻覺，並擴展其應用可能性。

---

## 專案內容

本專案為 MCP 相關簡報與資源彙整，內容涵蓋：
- MCP 協議介紹
- 架構說明
- MCP Server/Client 生態系
- 常見應用範例

---

## MCP 架構簡述

- **MCP Host**：負責客戶端與伺服器間通訊（如 Claude Desktop、Cursor、Raycast）
- **MCP Client**：發起請求的應用程式或服務，通常為 LLM 應用
- **MCP Server**：提供特定領域知識或功能，回應標準化上下文資料

### MCP Server 上下文來源
- **Prompts**：預設提示詞，可帶參數調用
- **Resources**：靜/動態資源，供 LLM 取得內容
- **Tools/Functions**：標準函式描述，允許 LLM 觸發特定行為

---

## 生態系與延伸資源

### 代表性 MCP Servers
- [Brave MCP Server](https://github.com/modelcontextprotocol/servers/blob/main/src/brave-search/README.md)
- [Playwright MCP Server](https://github.com/microsoft/playwright-mcp)
- [FileSystem MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)
- 更多請見 [Awesome MCP Servers](https://github.com/wong2/awesome-mcp-servers)

### 代表性 MCP Clients
- [VSCode](https://code.visualstudio.com/)
- [Cursor](https://www.cursor.com/)
- [Windsurf](https://windsurf.com/editor)
- [Cline](https://github.com/cline/cline)
- [Claude Desktop](https://claude.ai/download)
- [Chatwise](https://chatwise.app/)
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio)
- [RayCast](https://www.raycast.com/)
- 更多請見 [Awesome MCP Clients](https://github.com/punkpeye/awesome-mcp-clients)

---

## 延伸閱讀
- [MCP 官方網站](https://modelcontextprotocol.io/)
- [Awesome MCP Servers](https://github.com/wong2/awesome-mcp-servers)
- [Awesome MCP Clients](https://github.com/punkpeye/awesome-mcp-clients) 