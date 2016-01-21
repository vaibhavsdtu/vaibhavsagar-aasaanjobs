# vaibhavsagar-aasaanjobs

Set B:


Question 1:
void duplicate(int s[100])
{
static int a[100],i;
for(i=1;i<101;i++)
{
a[i]=0;
}
for(i=0; i<100;i++)
{
num=s[i];
a[num]++;
if(a[num]!=1)
{
cout<<"The number is repeated";
}}}




Question 3:

void main()
int sum,ele1,ele2,i,j,a[10];
int min=0;

for(i=0;i<10;i++)
{ 
for(j=0;j<10;j++)
{ 
if(i!=j)
{ 
sum=a[i]+a[j];
if(sum<0)
{
sum=-1*sum;
}

if(sum<min)
{
min=sum;
ele1=a[i];
ele2=a[j];
}}}}

cout<<"Minimum sum nearest to zero is"<<min
cout<<"Element 1"<<ele1;
cout<<"Element 2"<<ele2;
}


