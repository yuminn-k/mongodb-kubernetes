---
kind: fix
date: 2026-11-01
---

* **MongoDBCommunity**: Topology spread constraints removed from `spec.statefulSet.spec.template.spec.topologySpreadConstraints` are now removed from the StatefulSet. Previously the operator kept them. Fixes [#700](https://github.com/mongodb/mongodb-kubernetes/issues/700).
