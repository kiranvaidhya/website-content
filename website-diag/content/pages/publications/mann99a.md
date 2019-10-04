title: Power Analysis of a General Convolution Algorithm mapped on a Linear Processor Array
authors: R. Manniesing
has_pdf: True
template: publication
bibkey: mann99a
We explore the energy dissipation of the Linear Processor Array (LPA) as a function of the number of available resources (Processor Units P) within the array. This number P is an important parameter, as it reflects performance, relates parallel processing to energy dissipation, and influences the scaling of the various parts of the LPA architecture (memory, address generator, communication network). To make a comparison of the different design variants for a fixed datawidth possible, we propose a high-level energy dissipation model of the processor, which is based on a detailed analysis of a general convolution algorithm. It is shown that the energy dissipation of the LPA can roughly be described by the relationship Etotal ? N/P with N presenting the datawidth in pixels. This relationship is derived from two observations: first, the largest contribution to Etotal is formed by the energy dissipated by the memories, and second, in our model of the LPA, the datawidth of the memories corresponds with the number of pixels N to be processed, which results in an increase of the access rate when P decreases. Furthermore, we have shown that the energy dissipation caused by communication within the LPA, increases with increasing number of resources: the trade-off between communication versus computation in parallel computing. This turns out to be negligible in the total energy dissipation, and we therefore conclude, that the optimum solution is found, when a full number of resources is applied within the LPA.
