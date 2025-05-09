---
id: locking
title: Locking
summary: API for preventing accidental changes to annotations by locking them, with methods to lock/unlock individual or all annotations
---

# Locking

Annotations can be locked to avoid accidental changes. You can use
the locking API to lock/unlock annotations.

## API

There are various APIs for locking and unlocking annotations along with get/set methods

```js
import { annotation } from '@cornerstonejs/tools';

// locking of an annotation
annotation.locking.setAnnotationLocked(annotationUID, (locked = true));

// get all the locked annotations
annotation.locking.getAnnotationsLocked();

// unlock all annotations
annotation.locking.unlockAllAnnotations();
```

## Read more

:::note TIP
Read more about the locking API [here](/docs/api/tools/namespaces/annotation/namespaces/locking)
:::
