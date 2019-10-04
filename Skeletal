#include<stdio.h>
#include<string.h>

unsigned char code[] = \
"Enter your shellcode here";

main()
{

	printf("Shellcode Length:  %d\n", strlen(code));

	int (*ret)() = (int(*)())code;

	ret();

}

