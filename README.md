# Advanced Techniques for Large Language Models

Το πρόγραμμα εστιάζει σε προχωρημένες τεχνικές σχεδιασμού, προσαρμογής και βελτιστοποίησης Μεγάλων Γλωσσικών Μοντέλων (LLMs) και απευθύνεται σε αποφοίτους Πληροφορικής που επιθυμούν να αναπτύσσουν σύγχρονες, αξιόπιστες και αποδοτικές εφαρμογές Τεχνητής Νοημοσύνης. Καλύπτονται εξειδικευμένες μέθοδοι prompt engineering (advanced prompting patterns, chain-of-thought, self-refinement, test-time inference κ.λπ.), καθώς και τεχνικές parameter-efficient fine-tuning όπως LoRA και adapters.

Ιδιαίτερη έμφαση δίνεται σε Retrieval-Augmented Generation (RAG), με σχεδιασμό πλήρων pipelines που περιλαμβάνουν embedding models, vector databases, στρατηγικές chunking και reranking, καθώς και μεθόδους αξιολόγησης ποιότητας και ακρίβειας. Καλύπτονται επίσης θέματα ανάπτυξης LLM-based Agents (π.χ. tool-based reasoning, ReACT, LangChain, LangGraph). Παρουσιάζονται επίσης τεχνικές βελτιστοποίησης μοντέλων για παραγωγική χρήση, όπως quantization, distillation και inference optimization, με στόχο τη μείωση κόστους, χρόνου απόκρισης και ενεργειακών απαιτήσεων.

Μέσα από εκτενή εργαστηριακά παραδείγματα, οι συμμετέχοντες υλοποιούν end-to-end LLM εφαρμογές για πραγματικά σενάρια εργασίας, όπως έξυπνη αναζήτηση και ανάλυση εγγράφων, αυτοματοποίηση τεχνικής υποστήριξης, αυτόματη χρήση προγραμματιστικών εργαλείων από LLMs (“tool calling”), ανάπτυξη LLM agents, ανάλυση δεδομένων και υποστήριξη λήψης αποφάσεων. 

Με την ολοκλήρωση του προγράμματος, οι εκπαιδευόμενοι θα είναι σε θέση να σχεδιάζουν, να προσαρμόζουν και να ενσωματώνουν LLM συστήματα σε παραγωγικά περιβάλλοντα με τεχνική επάρκεια και επαγγελματικό προσανατολισμό.


## Κοινό
Το πρόγραμμα απευθύνεται κυρίως σε αποφοίτους Πληροφορικής ή συναφών επιστημών με βασική εμπειρία σε προγραμματισμό και μηχανική μάθηση. Απευθύνεται σε Μηχανικούς Λογισμικού, Data Scientists, ML/AI Engineers και ερευνητές που επιθυμούν να εμβαθύνουν σε προχωρημένες τεχνικές αξιοποίησης Μεγάλων Γλωσσικών Μοντέλων. Είναι κατάλληλο για επαγγελματίες που εργάζονται ή στοχεύουν να εργαστούν σε ανάπτυξη LLM εφαρμογών, συστήματα RAG, LLM Agents, fine-tuning μοντέλων, βελτιστοποίηση inference και ενσωμάτωση LLMs σε παραγωγικά περιβάλλοντα.

## Προαπαιτούμενα
Απαιτούνται σπουδές Πληροφορικής ή συναφούς αντικειμένου, βασικές γνώσεις προγραμματισμού, καλή γνώση Python, και κατανόηση εννοιών μηχανικής μάθησης. Οι ενδιαφερόμενοι θα πρέπει να προσκομίσουν πτυχίο ή αναλυτική βαθμολογία και αποδεικτικό επαρκούς γνώσης αγγλικής γλώσσας. 

## Αξία
Με την επιτυχή ολοκλήρωση του προγράμματος, οι εκπαιδευόμενοι θα έχουν αποκτήσει εξειδικευμένες δεξιότητες στον σχεδιασμό, την ανάπτυξη, προσαρμογή και βελτιστοποίηση LLM συστημάτων, επαρκείς για άμεση αξιοποίηση σε παραγωγικά περιβάλλοντα, έρευνα και σύγχρονες εφαρμογές Τεχνητής Νοημοσύνης.

## Θεματικές ενότητες

### Βασικές Αρχές και Αρχιτεκτονική Μεγάλων Γλωσσικών Μοντέλων [2 δίωρα]

- Βασικές αρχές και αρχιτεκτονική Transformers, sub-word tokenization, στάδια εκπαίδευσης LLMs (pre-training, instruction tuning, reinforcement learning from human/AI feedback)
- Οικογένειες μοντέλων, μοντέλα με ανοιχτά ή κλειστά βάρη, σε τοπικά ή online περιβάλλοντα 
- Περιορισμοί, biases, hallucinations, controllability

### Προχωρημένο Prompt Engineering & Reasoning [2 δίωρα]

- Advanced prompting patterns
- Chain-of-thought, self-consistency, self-refinement, test-time inference
- Prompt evaluation & robustness

### Fine-tuning, Reinforcement Learning και Parameter-Efficient Adaptation [4 δίωρα]
- Fine-tuning vs. prompting
- LoRA, adapters
- Reinforcement Learning from Human/AI Feedback (π.χ. DPO, GRPO)
- Dataset design & evaluation
- Overfitting, generalization, safety

### Retrieval-Augmented Generation (RAG) Systems και LLM-based Agents [4 δίωρα]
- Embeddings & vector databases
- Chunking, indexing, reranking
- End-to-end RAG pipelines
- Tool-based reasoning, ReACT, LangChain, LangGraph
- Evaluation, error analysis, optimization

### Βελτιστοποίηση, Deployment και Παραγωγική Χρήση LLMs [4 δίωρα]
- Quantization, distillation, inference optimization
- Cost/latency trade-offs
- Mini-project: end-to-end LLM application
