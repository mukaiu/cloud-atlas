.. _pi_storage_cluster:

=======================
树莓派存储集群
=======================

对于个人(其实企业也是)而言， :ref:`arm` 架构的低功耗(甚至可以做到无风扇静音)非常适合构建NAS: 想象一下，一台安静的存储在房间的角落里7x24小时进行提供数据存储、备份，随时能够访问海量的数据。

不过，对于我而言，我更想构建一个 :ref:`kubernetes` 集群来运行各种复杂的服务，以磨练自己的技术。那么是否可以使用树莓派来实现这个目标，一直是我心心念念的愿景:

- 我曾经 :ref:`arm_k8s_deploy` 和 :ref:`pi_k3s_deploy` ，现在我想进一步在k8s集群上通过 :ref:`rook` 来部署 :ref:`ceph` 存储

  - 模拟构建大规模
