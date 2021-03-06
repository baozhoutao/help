## 会签节点

- 会签节点允许多人同时审批，即处理人可以是2个或2个以上的人，审批时必须选择核准或驳回。
- 会签节点的驳回不同于审批节点的驳回，不能退回到任意一个已经流转过的步骤。当所有会签节点的处理人都审批完成后，不管是否其中有人进行了驳回都将根据流程设置进入到下一步骤，由下一步骤的人员来汇总处理意见，根据意见来选择后续节点。
- 管理员在设置时，可以指定一个相对小的范围，让上一个节点的处理人审批完成后在这个范围内选择任意多个处理人（免费版只能最多选择2人）。具体如何设置，参考[节点处理人](flow_step_user.md)。

####注意：

“会签”节点后面不允许再紧接着另一个“会签”节点。建议二者之间增加一个类似于“秘书汇总意见”的节点，指定好具体的某个人员，来综合第一个会签节点的意见，再来选择第二个会签节点的处理人员。

