# multivariate_normal_distribution
![다변량 정규분포](./images/MultivariateNormal.png)
- $정규분포 N(\mu, \sigma) \\
\mu는 평균(mean) \\ 
\sigma^2는 분산(variance)$ \
=> 두 개의 변수로 정의된다
- standard deviation($\sigma$) = sqr of variance 
- 1차 정규분포의 probability density function
$$f(x \vert \mu,\sigma^2) = \frac{2}{\sqrt{2\pi\sigma^2}}e^{\frac{(x-\mu)^2}{2\sigma^2}}$$
- standard normal distribution N(0,1) \
평균이 0, 분산이 1인 정규분포다


- 다차원으로 확장된 정규분포 = 다변량 분포
  - 공분산 행렬이 대각행렬인 등방성 다변량 정규분포를 사용
  - multivariate standard normal distribution N(0,I): 평균벡터가 0이고, 공분산 행렬이 단위벡터인 분포


