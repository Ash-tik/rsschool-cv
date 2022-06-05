# Alexandr Zhurikho
***
Contacts:
---
* Discord: Ash_sf#2283
* E-mail: a.zhurikho@gmail.com
* Tel: +79169581669

About myself:
---
I strive to develop and learn new things

Code example:
---
    int main()
    {
    	setlocale(LC_ALL, "Russian");
    	double c, k, t2;
    	printf_s("Введите c\n c=");
   	  scanf_s("%lf", &c);
     	printf_s("Введите k\n k=");
  	  scanf_s("%lf", &k);
  	  printf_s("|c+k|=%4.2lf\n", fabs(c+k));
  	  if (fabs(c + k) > 2) {
  		  t2 = pow(tan(c - 2 * k), 2);
  		  printf_s("|c+k|>2 \n t2=%4.2lf\n", t2);
  	  }
  	  else if (0.5 < fabs(c + k) && fabs(c + k) <= 2) {
  		  	t2 = log(fabs(c - 2 * k)) - sin(c / 2 / k);
  			  printf_s("0.5<|c+k|<=2 \n t2=%4.2lf\n", t2);
  		  }
  		  else printf_s("Условие не выполняется!\n |c+k|<0.5\n");
        return 0;
    }

Work experience:
---
Own buisiness - *design of steel structures*

Education:
---
Belarusian National Technical University  
*civil and industrial engineering*
