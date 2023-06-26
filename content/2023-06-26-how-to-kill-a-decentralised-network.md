+++
title = "【译】如何摧毁去中心化网络（例如联邦网络）"
+++

> 原文：How to Kill a Decentralised Network (such as the Fediverse)
> 
> 链接：<https://ploum.net/2023-06-23-how-to-kill-decentralised-networks.html>
> 
> 作者：Ploum
> 
> 日期：2023年6月23日

<figure>
  <img alt="Meta: "MAY I JOIN YOU?" src="https://stockage.framapiaf.org/framapiaf/media_attachments/files/110/583/215/225/403/266/original/7abd28f529cbb631.jpeg" />
  <figcaption>Meta: "MAY I JOIN YOU?" by <a href="https://framapiaf.org/@davidrevoy/110583258129951932">David Revoy</a></figcaption>
</figure>

2023年了，整个互联网都在 GAFAM（Google，Apple，Facebook，Amazon 和 Microsoft） 帝国的掌控之下。全部吗？不是。因为有一些小部落还在抵抗，并且其中一些部落开始聚集，形成了“联邦网络”（Fediverse）。

在 Twitter 和 Reddit 的争论中，联邦网络开始引起人们的注意。人们开始真正地使用它。帝国也注意到了。

## 资本家反对竞争

正如 Facebook 的著名投资者彼得·蒂尔（Peter Thiel）所说，“竞争是给输家的”。是的，那些“市场总是正确”的伪信徒，在自己入局的领域并不想要自由竞争的市场，他们想要垄断。自成立以来，Facebook 一直非常小心地扼杀每一个竞争对手。最简单的方式就是收购可能会成为竞争对手的公司。Instagram、WhatsApp 等等，只是因为它们的产品吸引了用户，并且可能会给 Facebook 带来阴影而被收购。

但是联邦网络无法被收购。联邦网络是通过协议（ActivityPub）进行交互的非正式的服务器集群（an informal group of servers）。这些服务器甚至可以运行不同的软件（Mastodon 是最著名的，但您也可以使用Pleroma、Pixelfed、Peertube、WriteFreely、Lemmy 和许多其他软件）。

你无法收购一个去中心化的网络！

但还有另一种方式：使其变得无关紧要。这正是谷歌对 XMPP 所做的。

## 谷歌如何加入 XMPP 联邦

在 20 世纪末，即时通讯程序（IM）非常流行。其中ICQ在早期非常成功，很快就被 MSN Messenger 跟进。MSN Messenger 就是当时的 Tiktok：一个没有成年人，青少年可以沉浸几小时甚至几天的世界。

由于 MSN 属于微软，谷歌要想与之抗衡，于是将 2005 年推出的 Google Talk 包含在 Gmail 界面中。要知道在当时，没有智能手机，Web应用程序非常少，应用程序必须安装在计算机上，Gmail 作为 Web 应用是开创性的。MSN 甚至一度与 Windows 操作系统捆绑在一起，并且难以卸载。通过 Gmail Web 页面构建 Google chat 是一种比操作系统内置软件更接近客户的方式。

当谷歌和微软为霸权而战时，自由软件极客们试图构建分布式即时通讯。像电子邮件一样，XMPP是一种联邦协议：多个服务器可以通过协议互相通信，并且每个用户通过客户端连接到一个特定的服务器。该用户随后可以使用任何客户端与任何服务器上的任何用户进行通信。这仍然是 ActivityPub 和 联邦网络的工作原理。

2006 年，Google Talk 开始兼容 XMPP。谷歌对 XMPP 是认真的。2008年，在我工作的时候，手机响了。电话那头说：“Hi，我们来自谷歌，想雇用您”。我打了几个电话，最终发现他们是通过 XMPP-dev 列表找到我的，他们正在找 XMPP 服务器系统管理员。

因此，谷歌是真的在拥抱联邦制。酷不酷？这意味着突然之间，每个 Gmail 用户都变成了一个 XMPP 用户。这对于 XMPP 只会有好处，对吧？我简直欣喜若狂。

## 谷歌如何杀死 XMPP

当然，现实并不那么光鲜亮丽。首先，尽管合作开发了 XMPP 标准，但 Google 仍在进行自己的闭源实现，没有人可以审查。事实证明，他们并不总是遵守他们正在制定的协议。他们没有实现所有功能。这迫使 XMPP 放慢开发来适应他们。很多新功能因为不兼容 Google Talk 而没有被实现或未在XMPP客户端中使用（例如头像花费了很长时间才在 XMPP 中出现）。联邦系统有时无法工作：在数小时或数天内，谷歌和常规 XMPP 服务器之间可能无法通信。XMPP 社区成为谷歌服务器的监控和调试人员，发布异常和宕机报告（我干过很多次，这可能是我得到工作机会的原因）。

由于 Google Talk 用户远远超过“真正的 XMPP”用户，因此没有什么“忽略 Google Talk 用户”的余地。加入 XMPP 但没有成为 Google Talk 用户的新人非常失望，因为他们的大多数联系人都是 Google Talk 用户。他们认为他们可以轻松地与他们通信，但体验上等同于使用 Google Talk 的残次版本。典型的 XMPP 花名册主要由 Google Talk 用户组成，外加几个极客。

2013 年，谷歌意识到大多数 XMPP 交互都是在 Google Talk 用户之间进行的。他们没有意愿去遵守一个不完全受其控制的协议。因此，谷歌终止了合作，宣布他们将不再支持联邦协议。然后开始了漫长的创建通讯应用的旅程，从Hangout（随后是 Allo、Duo 等等，后面我数不过来了）开始。

正如所料，没有一个谷歌用户留意到这个改变。事实上，他们谁也没有意识到。最糟糕的也不过是，他们的一些联系人下线了，就这些。但对于 XMPP 联邦系统来说，就像大多数用户突然消失了一样。即使是 XMPP 的顽固狂热分子，也不得不创建谷歌帐户以与朋友保持联系。还记得吗：对于他们，我们只是离线了。这是我们的错。

虽然 XMPP 仍然存在并且是一个非常活跃的社区，但它从未从这一打击中恢复过来。对谷歌采用的过高期望导致了巨大的失望，并悄然被遗忘。XMPP 变得非常小众。太小众了，以至于当群聊成为潮流时（如 Slack、Discord），自由软件社区重新发明了它（Matrix）来竞争，而 XMPP 早就可以群聊。（免责声明：我从未研究过 Matrix 协议，因此不知道它在技术上与 XMPP 相比如何。我只是认为它重新造了轮子，并且与 XMPP 在相同的领域竞争）。

如果谷歌从未加入 XMPP 或从未被视为其中一部分，XMPP 今天会有所不同吗？没有人能回答。但我确信它会增长得更缓慢，甚至可能更健康。它会比今天更大众、更重要，它会成为默认的去中心化通信平台。有一点可以肯定：如果谷歌没有加入，XMPP 不会比今天糟糕。

## 这并不是第一次发生：微软的剧本

谷歌对 XMPP 所做的并不是新鲜事。实际上，在1998年，微软工程师 Vinod Vallopllil 明确写了一篇题为“削弱开源攻击”的文章，在其中建议“对协议和应用程序去商品化……通过扩展这些协议和开发新协议，我们可以阻止开源项目进入这个市场。”

微软在发布 Windows 2000时，将这一理论付诸实践，该系统提供了对 Kerberos 安全协议的支持。但该协议得到了扩展。这些扩展的规范可自由下载，但需要接受许可证，禁止你实施这些扩展。一旦你点击“确定”，就不能使用任何开源版本的 Kerberos。其目标非常明确，就是要杀死任何竞争的网络项目，如 Samba。

Glyn Moody 在他的《叛逆代码》一书中披露了这一轶事，证明杀死开源和去中心化项目确实是有意识的目标。它从来不是随机发生的，也不是因为运气不好。

微软在办公市场上使用了类似的策略，利用专有格式（文件格式可以看作是交换数据的协议）确保了在办公市场上的主导地位。当替代方案（OpenOffice 然后是 LibreOffice）打开 doc/xls/ppt 格式变得足够好时，微软发布了一种他们称之为“开放和标准化”的新格式。该格式故意非常复杂（有20000页的规范！），最重要的是，是错误的。是的，规范中引入了一些 bug，这意味着实现完整 OOXML 格式的软件会与 Microsoft Office 表现不同。

这些 bug 以及政治游说，是慕尼黑市撤销其 Linux 迁移计划的原因之一。所以，是的，这个策略非常成功。今天 docx、xlsx 和 pptx 仍然是主流格式，正是得益于这一策略。信息来源：我曾经在那里工作，间接受雇于慕尼黑市政府，帮助 LibreOffice 的 OOXML 渲染更接近 Microsoft 的，而不是遵从规范。

更新：这种策略甚至拥有自己的维基百科页面。

[拥抱、扩展再消灭](https://zh.wikipedia.org/wiki/%E6%8B%A5%E6%8A%B1%E3%80%81%E6%89%A9%E5%B1%95%E5%86%8D%E6%B6%88%E7%81%AD)

## Meta 和联邦网络

不懂历史的人注定会重蹈覆辙。这正是 Meta 和联邦网络现在发生的事情。

有传言称，Meta 将兼容联邦网络。你可以从你的 Mastodon 账户关注 Instagram 上的人。

我不知道这些传言是否属实，Meta 是否真的考虑过。但我自己在 XMPP 和 OOXML 方面的经验告诉我一件事，如果 Meta 加入联邦网络，那么 Meta 将是唯一赢家。事实上，用户的反应显示他们已经取得了优势：联邦网络分裂成支持 Meta 的一方和反对 Meta 的一方。如果这种情况发生，这将意味着一个破碎的、令人沮丧的双层联邦网络，对新人几乎没有吸引力。

更新：这些传言已被证实，一位来自 fosstodon.org 的 Mastodon 管理员 Kev 已被邀请参加 Meta 的非公开会议。他做出了最好的回应：礼貌地拒绝，并且最重要的是，公开了邮件以对用户保持透明。谢谢 Kev！

[Mail from Meta to Kev, from Fosstodon, and reply](https://fosstodon.org/@kev/110592625692688836)

我们梦想着让所有的朋友和家人都加入联邦网络，以便完全避开专有网络。但联邦网络并不寻求市场主导地位或利润。联邦网络不寻求增长。它提供一个自由的空间，加入联邦网络的人是那些寻求自由的人。如果人们没有准备好或者不寻求自由，那也没关系。他们有权利留在专有平台上。我们不应该强迫他们加入联邦网络。我们不应该不计一切代价地纳入尽可能多的人。我们应该诚实，并确保人们是因为共享其中的某些价值观而加入联邦网络。

与 Meta 比拼不计代价地盲目增长，我们肯定会输。他们是此类游戏的大师级玩家。他们试图把每个人都带到他们的领地，让人们使用他们所销售的武器来与他们竞争。

联邦网络只能通过坚持自己的立场，通过谈论自由、道德、伦理和价值观来获得胜利。通过引发公开的、非商业化的、非监视性的讨论来获得胜利。通过承认目标不是要赢、也不是去拥抱来获得胜利。联邦网络的目标是保持工具的本质。这是一个为人类相互联结提供自由空间的工具。这是任何商业实体都永远无法真正提供的东西。

---

作为一名写作者和工程师，我喜欢探索技术如何影响社会。您可以通过 [电子邮件](https://listes.ploum.net/mailman3/postorius/lists/en.listes.ploum.net/) 或 [RSS](https://ploum.net/atom_en.xml) 订阅我的文章。我珍视隐私，不会泄露您的地址。

如果您能阅读法语，您可以通过购买/分享/阅读我的 [书籍](https://ploum.net/livres.html) 并订阅我的法语 [newsletter](https://listes.ploum.net/mailman3/postorius/lists/fr.listes.ploum.net/) 或 [RSS](https://ploum.net/atom_fr.xml) 中的新闻通讯来支持我。我也开发 [自由软件](https://ploum.net/software.html)。