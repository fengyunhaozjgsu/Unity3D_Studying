# Unity3D_Studying
一些我学习Unity3D的小记录
[RequireComponent(typeof (CharacterController))]//添加组件功能
[SerializeField] private bool m_IsWalking;//序列化在ui界面显示，方便调试
CharacterController建议你每帧只调用一次Move或者SimpleMove。
