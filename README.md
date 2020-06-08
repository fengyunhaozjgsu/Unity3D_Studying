# Unity3D_Studying
##### 一些我学习Unity3D的小记录<br />
[RequireComponent(typeof (CharacterController))]//添加组件功能<br />
[SerializeField] private bool m_IsWalking;//序列化在ui界面显示，方便调试<br />
CharacterController建议你每帧只调用一次Move或者SimpleMove<br />
<br />
<br />
CharacterController建议你每帧只调用一次Move或者SimpleMove。
<br />void OnGUI()
<br />    {
<br />        GUI.Box(new Rect(10, 40, hearlthBarLenth, 20), curHealth + "/" + maxHealth);
<br />    }
GameObject go = GameObject.FindGameObjectWithTag("player");<br />
GameObject[] go = GameObject.FindGameObjectsWithTag("player");或者直接find名称<br />
GetComponent<Renderer>().material//动态设置组件属性<br />
