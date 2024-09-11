# <small>void</small> $kernel(<small>e: any, l: any</small>)
Used to create `system42`.

!> It is recommended that you only use [`$kernel.data._apps`](/api/interfaces/KernelData.md#objectltstringappgt-_apps) (or `le._apps`). Modifying anything else may corrupt your installation.
## Properties
### <small>[KernelData](/api/interfaces/KernelData.md)</small> data
The data inside the kernel. Used for creating and modifying apps through the `_apps` property. `le` is a reference to this.
### <small>Object</small> observers
Possibly a list of `MutationObserver`s.
### <small>boolean</small> paused
### <small>Object</small> ready
### <small>Object</small> tasks
## Methods
### <small>void</small> config(<small>e: Object</small>)
### <small>unknown</small> launch(<small>t: any</small>)
### <small>void</small> off(<small>eventName:&nbsp;[KernelEventName](api/types/KernelEventName.md), callback: (...args: any) => void</small>)
### <small>void</small> on(<small>eventName:&nbsp;[KernelEventName](api/types/KernelEventName.md), callback: (...args: any) => void</small>)
### <small>void</small> once(<small>eventName:&nbsp;[KernelEventName](api/types/KernelEventName.md), callback: (...args: any) => void</small>)
### <small>unknown</small> parallel(<small>r: any, a: any</small>)
### <small>unknown</small> series(<small>e: any, a: any</small>)
### <small>unknown</small> stop(<small>e: any</small>)
### <small>unknown</small> task(<small>e: any, n: any</small>)
### <small>unknown</small> trigger(<small>n: any</small>)
## Returns
`undefined`.