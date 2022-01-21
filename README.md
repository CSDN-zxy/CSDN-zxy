#define _CRT_SECURE_NO_WARNINGS 1
#include "router.h"

//处理数据包的输入
LL Getinput()
{
	pf = fopen("date.txt", "r+");
	if (pf == NULL)
	{
		return 0;
	}
	return 1;
}

//获取规则集元素的指针
LL Getrule()
{
	rf = fopen("rule.txt", "r");

}
