# AI Passport
Work presented to the Medical Informatics Europe Conference (MIE) 2024

## Summary
A proposal for the implementation of the AI Passport in JSON format by the [BDSLab](https://bdslab.upv.es/) at Universitat Politecnica de Valencia. A human-readable JSON is included describing every field and the type of data needed. A [Pydantic](https://docs.pydantic.dev/latest/) model is also included so Passport file can be validated following this schema. We have also included the json validator file exported from the pydantic model.

### Article abstract

The integration of Artificial Intelligence (AI) in healthcare signifies a substantial shift, offering benefits to patients and healthcare systems while also introducing new risks. The emphasis on patient safety and performance standards is pivotal, especially with the European Union's strides towards regulating AI through the AI Act. This act focuses on classifying AI systems based on risk levels, mandating stringent requirements for high-risk AI, enhancing transparency, and ensuring ethics in AI applications. The concept of an "AI passport" is introduced as a living document detailing the AI system's purpose, ethical declarations, training, evaluation, and potential biases. This passport aims to enhance transparency and safety in medical AI applications, serving as a comprehensive record for patients, clinicians, and stakeholders. The AI passport, structured in JSON format, encapsulates key information about the AI system as a mechanism for continuous performance evaluation and transparency. This initiative may represent a significant step towards mitigating the risks associated with AI in healthcare, emphasizing the importance of accountability, transparency, and patient safety in the development and application of AI technologies.