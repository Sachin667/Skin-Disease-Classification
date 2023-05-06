# Skin-Disease-Classification
Skin Disease Classification / Multiclass classification

This database contains 34 attributes, 33 of which are linear valued and one of them is
nominal.The differential diagnosis of erythemato-squamous diseases is a real problem
in dermatology. They all share the clinical features of erythema and scaling, with very
little differences. The diseases in this group are psoriasis, seboreic dermatitis, lichen
planus, pityriasis rosea, cronic dermatitis, and pityriasis rubra pilaris. Usually a biopsy is
necessary for the diagnosis but unfortunately these diseases share many
histopathological features as well. Another difficulty for the differential diagnosis is that a
disease may show the features of another disease at the beginning stage and may have
the characteristic features at the following stages. Patients were first evaluated clinically
with 12 features. 
* **Task 1 :-Prepare a complete data analysis report on the given data.**
* **Task 2 :-Create a predictive model using machine learning techniques to predict
the various classes of skin disease.**
* **Task 3 :-Suggestions to the Doctors to identify the skin diseases of the patient at
the earliest.**

Afterwards, skin samples were taken for the evaluation of 22
histopathological features.
* **CLINICAL FEATURES**
*
* **Erythema** - Erythema is redness of the skin or mucous membranes(magnitude scale between 0 and 3)
* **Scaling** -Scales occur when the outermost layer of the epidermis becomes dry and flaky and peels(magnitude scale between 0 and 3)
* **Definite borders**-visible borders and appears are spread in the skin(magnitude scale between 0 and 3)
* **Itching** -Irritation of the skin that is uncomfortable and results in scratching(magnitude scale between 0 and 3)
* **koebner phenomenon**-The Koebner phenomenon is typically associated with preexisting skin disease(Psoriasis, vitiligo, lichen planus)
* **polygonal papules**-polygonal Papules are often called skin lesions, which are essentially changes in your skin’s color or texture(magnitude scale between 0 and 3)
* **Follicular papules**-Follicular erythematous papules and follicular pustules on hair-bearing skin are a feature of superficial follicular(magnitude scale between 0 and 3)
* **Oral mucosal involvement**- mucous membrane is affected by psoriasis or lichen planus skin diseases(magnitude scale between 0 and 3)
* **knee and elbowinvolvement**-The skin of the knees and elbows are frequent sites of trauma, including abrasions and contusions(magnitude scale between 0 and 3)
* **scalp involvement**-scalp involvement related to skin disease and its magnitude (between 0 and 3)
* **Family history**-Whether the patient's family members have the same diseases or not(0-NO,1-YES)
* 
* **HISTOPATHOLOGICAL ATTRIBUTES**
*
* **Melanin incontinence**-Melanin incontinence (pigmentary incontinence) is the presence of melanin in the superficial dermis, due to the loss of melanin from damaged cells of the basal layer(magnitude scale between 0 and 3)
* **Eosinophils in the infiltrate**-Eosinophil infiltration is a common finding in a broad spectrum of skin diseases, despite the fact that the skin is devoid of eosinophils under physiologic conditions(magnitude scale between 0 and 3)
* **PNL infiltrate**-A predominantly neutrophilic infiltrate of the dermis means a large number of neutrophils inferred to have migrated into the skin(magnitude scale between 0 and 3)
* **Fibrosis of the papillary dermis**-Fibrosis may occur as a subtle finding, particularly in the later stages. It is characterized by proliferation of fibroblasts and collagen fibers in the dermis or around hair follicles, typically oriented parallel to the epidermis(magnitude scale between 0 and 3)
* **Exocytosis**-Exocytosis is a means of membrane transportation that expels the intracellular material out of the cell,Exocytosis is infiltration of the epidermis by inflammatory or circulating blood cells(magnitude scale between 0 and 3)
* **Acanthosis**-Acanthosis is (diffuse epidermal hyperplasia) thickening of the skin due to the diseases and this magnitude diifference categorize the skin diseases easily(magnitude scale between 0 and 3)
* **Hyperkeratosis**-Hyperkeratosis refers to thickening of your skin's outer layer(magnitude scale between 0 and 3)
* **Parakeratosis**-this process leads to the abnormal replacement of annular squames with nucleated cells(magnitude scale between 0 and 3)
* **clubbing of the rete ridges**-rete ridge, One of the downgrowths of epithelium surrounding the connective tissue papillae in the irregular internal surface of the epidermis(magnitude scale between 0 and 3)
* **Elongation of the rete ridges**-It is mosly assocaited with psoriasis and seborrheic dermatitis diseases. Elongation of the rete ridges in the skin with melanocyte proliferation in the basal layer(magnitude scale between 0 and 3)
* **Thinning of the suprapapillary epidermis**-it is usually common is psoriasis skin disease,This was defined as a thinning of the granular layer at the tips of the papillae(magnitude scale between 0 and 3)
* **Spongiform pustule**-The spongiform pustule forms through the migration of neutrophils from the papillary dermal capillaries to the upper layer of epidermis(magnitude scale between 0 and 3)
* **Munro microabcess**- These were defined as the presence of collections of neutrophils in the corneal layer and the stratum spinosum respectively(magnitude scale between 0 and 3)
* **focal hypergranulosis**-Hypergranulosis is an increased thickness of the stratum granulosum(magnitude scale between 0 and 3)
* **Disappearance of the granular layer**- The layer of follicle cells lining the theca of the vesicular ovarian follicle; called also granular layer. it is disappread or not,if yes what is the magnitude(magnitude scale between 0 and 3)
* **vacuolisation and damage of basal layer**-In dermatopathology "vacuolization" often refers specifically to vacuoles in the basal cell-basement membrane zone area, where it is an unspecific sign of disease(magnitude scale between 0 and 3)
* **Spongiosis**-Spongiosis can occur in the early stages of psoriasis associated with lymphocyte exocytosis,Spongiosis is mainly abnormal accumulation of fluid in the epidermis(magnitude scale between 0 and 3)
* **Saw tooth appearance of rete**- The normal “U-shaped” rete ridges become pointed resembling a “saw tooth”, hence the name. The rete ridge, in these lesions, assumes this shape due to the basal cell degeneration of the epithelium by the subjacent inflammatory cells..(magnitude scale between 0 and 3)
* **Follicular horn plug**-Follicular plugging is an abnormal accumulation of keratin at the shoulder region of the hair follicle in response to an inflammatory reaction..it is asssociated with pityriasis rubra pilaris skin disease(magnitude scale between 0 and 3)
* **perifollicular parakeratosis**-Parakeratosis is a mode of keratinization characterized by the retention of nuclei in the stratum corneum(magnitude scale between 0 and 3)
* **inflammatory monoluclear inflitrate**-Mononuclear cell infiltration is observed first in the affected skin,reaches a peak at 2 weeks of age and resolves later in the course of the disease.This common is all skin diseases(magnitude scale between 0 and 3)
* **Band like infiltrate**-There is a band-like infiltrate of lymphocytes at the epidermal-dermal junction with damage to the basal cell layer and pigment incontinence,this feature is mainly associated with lichen planus disease(magnitude scale between 0 and 3)
* **AGE**-Patients Age
* 
