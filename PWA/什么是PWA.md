## 官方定义

Progressive Web Apps 是结合了 web 和 原生应用中最好功能的一种体验。对于首次访问的用户它是非常有利的, 用户可以直接在浏览器中进行访问，不需要安装应用。随着时间的推移当用户渐渐地和应用建立了联系，它将变得越来越强大。它能够快速地加载，即使在比较糟糕的网络环境下，能够推送相关消息, 也可以像原生应用那样添加至主屏，能够有全屏浏览的体验。



Progressive Web Apps 是:

- 渐进增强 - 能够让每一位用户使用，无论用户使用什么浏览器，因为它是始终以渐进增强为原则。
- 响应式用户界面 - 适应任何环境：桌面电脑，智能手机，笔记本电脑，或者其他设备。
- 不依赖网络连接 - 通过 service workers 可以在离线或者网速极差的环境下工作。
- 类原生应用 - 有像原生应用般的交互和导航给用户原生应用般的体验，因为它是建立在 app shell model 上的。
- 持续更新 - 受益于 service worker 的更新进程，应用能够始终保持更新。
- 安全 - 通过 HTTPS 来提供服务来防止网络窥探，保证内容不被篡改。
- 可发现 - 得益于 W3C manifests 元数据和 service worker 的登记，让搜索引擎能够找到 web 应用。
- 再次访问 - 通过消息推送等特性让用户再次访问变得容易。
- 可安装 - 允许用户保留对他们有用的应用在主屏幕上，不需要通过应用商店。
- 可连接性 - 通过 URL 可以轻松分享应用，不用复杂的安装即可运行。

Progressive Web Apps 涉及到的相关 Web APIs：

Cache  https://developer.mozilla.org/en-US/docs/Web/API/Cache
CacheStorage    https://developer.mozilla.org/en-US/docs/Web/API/CacheStorage\
Client https://developer.mozilla.org/en-US/docs/Web/API/Client
Clients https://developer.mozilla.org/en-US/docs/Web/API/Clients
ExtendableEvent https://developer.mozilla.org/en-US/docs/Web/API/ExtendableEvent
ExtendableMessageEvent https://developer.mozilla.org/en-US/docs/Web/API/ExtendableMessageEvent
FetchEvent https://developer.mozilla.org/en-US/docs/Web/API/FetchEvent
InstallEvent https://developer.mozilla.org/en-US/docs/Web/API/InstallEvent
Navigator.serviceWorker https://developer.mozilla.org/en-US/docs/Web/API/Navigator/serviceWorker
NotificationEvent https://developer.mozilla.org/en-US/docs/Web/API/NotificationEvent
ServiceWorker https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorker
ServiceWorkerContainer https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerContainer
ServiceWorkerGlobalScope https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerGlobalScope
ServiceWorkerMessageEvent https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerMessageEvent
ServiceWorkerRegistration https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerRegistration
SyncEvent https://developer.mozilla.org/en-US/docs/Web/API/SyncEvent
SyncManager https://developer.mozilla.org/en-US/docs/Web/API/SyncManager
SyncRegistration https://developer.mozilla.org/en-US/docs/Web/API/SyncRegistration
PeriodicSyncEvent https://developer.mozilla.org/en-US/docs/Web/API/PeriodicSyncEvent
PeriodicSyncManager https://developer.mozilla.org/en-US/docs/Web/API/PeriodicSyncManager
PeriodicSyncRegistration https://developer.mozilla.org/en-US/docs/Web/API/PeriodicSyncRegistration
WindowClient https://developer.mozilla.org/en-US/docs/Web/API/WindowClient
PushManager https://developer.mozilla.org/en-US/docs/Web/API/PushManager
GlobalFetch https://developer.mozilla.org/en-US/docs/Web/API/GlobalFetch
Request https://developer.mozilla.org/en-US/docs/Web/API/Request
Response https://developer.mozilla.org/en-US/docs/Web/API/Response
Body https://developer.mozilla.org/en-US/docs/Web/API/Body
