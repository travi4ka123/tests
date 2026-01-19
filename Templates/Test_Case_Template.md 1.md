```
---
ID: <% tp.system.prompt("ID тест-кейса:") %>
Priority: <% await tp.system.suggester(["smoke", "critical", "extended"], ["smoke", "critical", "extended"], false, "Выберите приоритет:") %>
Tags:
Status: Draft
---
# [ID]: [Название тест-кейса] 

...
```