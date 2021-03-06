![Alt Image Text](images/qa/qa0.jpg "headline image")

# K8S Issues List

1. [污点和容忍](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA1.md#1%E6%B1%A1%E7%82%B9%E5%92%8C%E5%AE%B9%E5%BF%8D)

2. [镜像时区问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA1.md#2-%E9%95%9C%E5%83%8F%E6%97%B6%E5%8C%BA%E9%97%AE%E9%A2%98)

3. [`kubelet sidecar`镜像问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA1.md#3-kubelet-sidecar%E9%95%9C%E5%83%8F%E9%97%AE%E9%A2%98) 

4. [`kubernetes` 集群访问外部服务](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA1.md#3-kubelet-sidecar%E9%95%9C%E5%83%8F%E9%97%AE%E9%A2%98)

5. [`Helm` 安装问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA2.md#1-helm-%E5%AE%89%E8%A3%85%E9%97%AE%E9%A2%98)

6. [`nodeAffinity` 问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA2.md#1-helm-%E5%AE%89%E8%A3%85%E9%97%AE%E9%A2%98)

7. [怎样理解 `ingress` 和 `ingress-controller`](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA2.md#3-%E6%80%8E%E6%A0%B7%E7%90%86%E8%A7%A3-ingress-%E5%92%8C-ingress-controller)

8. [`flannel` 网络问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA2.md#4-flannel-%E7%BD%91%E7%BB%9C%E9%97%AE%E9%A2%98)

9. [节点资源配置问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA2.md#5-%E8%8A%82%E7%82%B9%E8%B5%84%E6%BA%90%E9%85%8D%E7%BD%AE%E9%97%AE%E9%A2%98)
 
10. [`Helm` 命令补全方法](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA2.md#6-helm-%E5%91%BD%E4%BB%A4%E8%A1%A5%E5%85%A8%E6%96%B9%E6%B3%95)

11. [`docker` 启动 `jenkins` 问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA2.md#7-docker-%E5%90%AF%E5%8A%A8-jenkins-%E9%97%AE%E9%A2%98)

12. [节点资源驱逐问题 `DiskPressure`](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA3.md#1-%E8%8A%82%E7%82%B9%E8%B5%84%E6%BA%90%E9%A9%B1%E9%80%90%E9%97%AE%E9%A2%98)

13. [集群部署方式的选择](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA3.md#2-%E9%9B%86%E7%BE%A4%E9%83%A8%E7%BD%B2%E6%96%B9%E5%BC%8F%E7%9A%84%E9%80%89%E6%8B%A9)

14. [`kubectl` 出现 `no such host` 的错误](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA3.md#3-kubectl-%E5%87%BA%E7%8E%B0-no-such-host-%E7%9A%84%E9%94%99%E8%AF%AF)

15. [`kubeadm` 证书有效期问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA4.md#1-kubeadm-%E8%AF%81%E4%B9%A6%E6%9C%89%E6%95%88%E6%9C%9F%E9%97%AE%E9%A2%98)

16. [关于`java`应用中资源限制的问题 CPU and Memory](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA4.md#2-%E5%85%B3%E4%BA%8Ejava%E5%BA%94%E7%94%A8%E4%B8%AD%E8%B5%84%E6%BA%90%E9%99%90%E5%88%B6%E7%9A%84%E9%97%AE%E9%A2%98)

17. [Critical Pod 的使用](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA4.md#3-critical-pod-%E7%9A%84%E4%BD%BF%E7%94%A8)

18. [Prometheus 管理数据指标的方法(删除)](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA4.md#4-prometheus-%E7%AE%A1%E7%90%86%E6%95%B0%E6%8D%AE%E6%8C%87%E6%A0%87%E7%9A%84%E6%96%B9%E6%B3%95)

19. [`Statefulset Pod` 的管理策略](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA4.md#5-statefulset-pod-%E7%9A%84%E7%AE%A1%E7%90%86%E7%AD%96%E7%95%A5)

20. [`kubectl exec` 参数问题](https://github.com/Chao-Xi/JacobTechBlog/blob/master/k8s_tutorial/k8s_QA4.md#6-kubectl-exec-%E5%8F%82%E6%95%B0%E9%97%AE%E9%A2%98)


