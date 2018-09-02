# ベイズ					
* x から yを推定したい		yが原因、xが結果　など  
  * p(y|x) = p(x|y) / p(x) * p(y)		事後確率　＝　尤度　/ 周辺確率 * 事前確率		
* yが離散値（ex classification）のときは y = {C1, C2, .., Cn}				
  * p(Ci|x) = p(x|Ci) / p(x) * p(Ci)				
				
#  Maximum a posteriori（MAP）推定					
* y(x) = arg max_y p(y|x)		xに対して事後確率を最大とするy		
