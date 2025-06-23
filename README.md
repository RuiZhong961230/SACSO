# SACSO
Self-adaptive competitive swarm optimizer: a memetic approach for global optimization and human-powered aircraft design

## Abstract
This paper presents a memetic approach of Competitive Swarm Optimizer (CSO) named Self-Adaptive Competitive Swarm Optimizer (SACSO). We focus on two key parameters of CSO: scaling factor and population size and introduce a parameter sorting scheme and a linear population reduction strategy to enhance the performance of SACSO. Specifically, the parameter sorting scheme assigns smaller scaling factors to better-performing particle individuals to encourage exploitative searchability, while larger scaling factors are allocated to poor-performing particle individuals to promote exploration in unknown search areas. The linear population reduction strategy adapts to different optimization phases, emphasizing exploration in the early phase and enhancing exploitation in the later phase. To investigate the performance of SACSO, we conducted comprehensive numerical experiments on CEC2017, CEC2022, and seven classic engineering problems. The experimental results and statistical analysis demonstrate the competitiveness of SACSO against six state-of-the-art optimizers and four advanced CSO variants. Ablation studies further validate the contribution of the two introduced strategies. Finally, we applied SACSO to real-world Human-Powered Aircraft (HPA) design problems, and the results highlight the potential of SACSO for solving various real-world optimization challenges. The source code of SACSO is available at https://github.com/RuiZhong961230/SACSO.

## Citation
@article{Zhong:25,  
  title={Self-adaptive competitive swarm optimizer: a memetic approach for global optimization and human-powered aircraft design},  
  author={Rui Zhong and Zhongmin Wangg and Ibrahim Al-Shourbajig and Essam H. Housseing and Pramod H. Kachareg and Abdoh Jabbarig and Raimund Kirnerg and Jun Yu },  
  journal={Memetic Computing},  
  number={32},  
  volume={17},  
  year={2025},  
  publisher={Springer},  
  doi = {https://doi.org/10.1007/s12293-025-00465-3 },  
}

## Datasets and Libraries
CEC benchmarks are provided by opfunu==1.0.0 and the Human-Powered Aircraft (HPA) Design problems can be downloaded from https://github.com/Nobuo-Namura/hpa.

## Contact
If you have any questions, please don't hesitate to contact zhongrui[at]iic.hokudai.ac.jp
