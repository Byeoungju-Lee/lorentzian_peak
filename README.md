# lorentzian_peak

데이터 k=1000 ~ 8000/cm 사용.
0_dataset_1layer_use_fit.ipynb으로 제작한 데이터 n+k+thickness+level+R spectrum를 
FCL_made_in_torch.ipynb의 Unet으로 돌렸으나 두께가 지속적으로 불일치하는 결과가 발생.
Lorentzian_peak.ipynb로 데이터를 제작,
Dacon_paper의 Skipconnection으로 Deep learning을 진행했지만 이 경우에도 두께 불일치.
