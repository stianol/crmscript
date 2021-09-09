---
uid: crmscript_ref_XMLNode_addChild_XMLNode_node
title: XMLNode.addChild(XMLNode node)
intellisense: XMLNode.addChild
keywords: addChild(XMLNode)
so.topic: reference
so.yml: 1
---

# XMLNode.addChild(XMLNode node)

Add one node as a child node of the current node.

## Parameters

* **node:** The node to be added

## Example

```crmscript
XMLNode xml = XMLNode("root");
xml.setName("Root");
xml.setParameter("type", "object");
xml.setText("Example text");

XMLNode xMenu = XMLNode("menu");
xMenu.setParameter("type", "string");
xml.addChild(xMenu);
```