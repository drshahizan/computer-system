<a href="https://github.com/drshahizan/computer-system/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/computer-system" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/computer-system/network/members"><img src="https://img.shields.io/github/forks/drshahizan/computer-system" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/computer-system/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/computer-system" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/computer-system"><img src="https://img.shields.io/github/issues/drshahizan/computer-system" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/computer-system/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/computer-system?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2Fcomputer-system&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

## Case Study:

**Name: Zheng Qixiao** 

**Matrix No: MEC232025** 

## Answer
### Question 1: Which Benchmarking Tools Would You Recommend TechSolutions Inc. Prioritize for Evaluating CPU Performance, and Why?

To recommend benchmarking tools for TechSolutions Inc. in evaluating CPU performance, I suggest they prioritize **SPEC CPU** and **Geekbench** because they address both single-core and multi-core performance needs effectively, which is crucial for the CPU-intensive applications the company focuses on, like AI and data analytics.

#### SPEC CPU

**SPEC CPU** is a widely used benchmarking tool that provides detailed insights into CPU performance for complex, real-world tasks. It includes two main test types:
  
- **SPECint** (integer operations): Good for evaluating the CPU’s ability to handle typical application instructions and everyday workloads.
- **SPECfp** (floating-point operations): Essential for tasks that rely on heavy calculations, such as AI and data processing, which TechSolutions Inc. would use.

One advantage of SPEC CPU is that it measures **long-term performance**, which simulates the kinds of workloads the company’s CPUs will handle continuously in data centers. Since SPEC CPU has both single-threaded and multi-threaded tests, it’s perfect for understanding the CPU’s power for both **single-core** tasks and **multi-core** parallel processing, which are both important for AI and cloud applications.

#### Geekbench

**Geekbench** is another great tool to use alongside SPEC CPU because it’s fast and user-friendly, and it benchmarks both **single-core** and **multi-core** performance across a variety of real-world applications. Geekbench simulates common workloads like **image processing, cryptography, and machine learning tasks**, which match the kinds of services TechSolutions Inc. provides.

- **Single-core and Multi-core Tests**: Geekbench gives a quick snapshot of a CPU’s single-core capabilities, which is important for tasks that can’t be split across cores. It also has multi-core tests for understanding parallel processing power.
- **Cross-Platform Comparison**: Geekbench works on various platforms, so it makes it easy to compare performance across different hardware choices if the IT team is considering multiple configurations.

By using SPEC CPU to understand the CPU’s power for long, complex processing tasks and Geekbench for a broader set of real-world applications, TechSolutions Inc. will get a well-rounded view of each CPU option. This will help them choose hardware that balances **speed, reliability, and efficiency** across different workloads.

### Question 2: How Should TechSolutions Inc. Approach Storage Benchmarking to Ensure Optimal Data Retrieval Speed and Reliability for Its Cloud Computing Services?

To ensure optimal data retrieval speed and reliability for its cloud computing services, TechSolutions Inc. should use a combination of **CrystalDiskMark** and **AS SSD** to evaluate storage performance. These tools offer essential insights into both **sequential** and **random read/write speeds**, which are critical for cloud services that handle high-volume data access and transfer.

#### CrystalDiskMark

**CrystalDiskMark** is widely used for assessing **sequential read and write speeds**, which measure how well storage devices handle continuous data blocks. This is important for cloud computing services that require high throughput to manage large files, such as in data analytics or file storage systems.

- **Sequential Speeds**: CrystalDiskMark can provide clear metrics on the **maximum data transfer rates** for sequential operations, giving TechSolutions a solid benchmark for large file processing.
- **Random Access Speed**: Although primarily known for sequential speeds, CrystalDiskMark also assesses random read and write speeds, offering a preliminary view of how well the storage handles fragmented or scattered data.

#### AS SSD

**AS SSD** complements CrystalDiskMark by focusing more on **random access times**, which is essential for environments where data retrieval often involves small, random data reads and writes. For TechSolutions, where cloud computing applications frequently need rapid access to varied data sets, AS SSD helps determine how well a storage solution can handle this type of load.

- **4K Random Read/Write**: AS SSD tests small, 4K random read/write speeds, which simulate real-world conditions where data is accessed in smaller, dispersed chunks. This is critical for database queries or cloud applications that require frequent access to smaller data packets.
- **Latency and Access Time**: AS SSD provides insights into access latency, allowing TechSolutions to gauge how quickly data can be retrieved or written under real-world conditions.

#### Recommended Approach

To create a balanced evaluation, TechSolutions Inc. should:
1. Use **CrystalDiskMark** to measure sequential read/write performance, ensuring that the storage solution can handle high-throughput data operations.
2. Use **AS SSD** to focus on random access metrics, particularly for smaller, frequent data operations that are common in cloud environments.

This combined approach allows TechSolutions to assess both large-scale, continuous data handling (through CrystalDiskMark) and smaller, random access needs (through AS SSD). Together, these tools provide a comprehensive view of storage performance, which will help TechSolutions select a storage solution that ensures **both speed and reliability** in cloud computing services.

### Question 3: What Considerations Should the IT Team Keep in Mind Regarding Power Efficiency When Selecting Hardware Based on Benchmarking Results?

When selecting hardware for TechSolutions Inc., power efficiency is a critical factor to manage long-term operational costs in a data center environment. The IT team should pay close attention to both **idle power consumption** and **performance per watt (Perf/Watt)** metrics to ensure energy-efficient yet powerful systems that meet processing demands.

#### Idle Power Consumption

In data centers, hardware often spends significant time in an idle or low-activity state. Evaluating **idle power consumption** helps the IT team estimate baseline power costs, especially important for systems that may not always operate at full capacity. Choosing hardware with low idle power can lead to substantial cost savings over time.

- **Energy Savings**: Hardware with lower idle power consumption reduces overall energy costs and environmental impact, as the systems consume less power when not under load.
- **Cooling and Infrastructure**: Lower idle power consumption also decreases the strain on cooling systems, allowing TechSolutions to reduce costs associated with climate control in the data center.

#### Performance per Watt (Perf/Watt)

**Performance per watt (Perf/Watt)** is a key metric for evaluating the **energy efficiency** of a system under load. This metric measures how much computational power a machine can deliver for each watt of power it consumes, giving insight into which configurations provide optimal performance without excessive energy use.

- **Efficient Processing**: High Perf/Watt values are ideal for CPU- and GPU-intensive tasks common in AI processing, allowing TechSolutions to achieve maximum productivity while controlling energy costs.
- **Cost-Effective Scaling**: For applications that require sustained high performance, such as data analytics or machine learning workloads, high Perf/Watt systems can reduce long-term expenses by balancing processing power with power consumption.

#### Recommended Approach

By focusing on both **idle power consumption** and **Perf/Watt**, the IT team at TechSolutions Inc. can make cost-effective decisions that meet the company’s needs for **energy efficiency, reliability, and performance**. This approach will help minimize operational expenses over the lifespan of the hardware, contributing to a more sustainable data center while optimizing power use for CPU- and GPU-heavy applications.


## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/computer-system/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

