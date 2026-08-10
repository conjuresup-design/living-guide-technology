# Observation Before Interpretation

**Publication ID:** LGT-OBS-001

**Publication Version:** 1.0.0

**Framework Version:** 1.0.0

**Classification:** Normative

**Status:** QA Ready - Draft Baseline

**Release Date:** 2026-08-09

## Executive Statement

A Living Guide SHALL distinguish what was observed from what was inferred. Observation Before Interpretation establishes the architectural boundary that prevents raw evidence, bounded observation, interpretation, and conclusion from collapsing into one another. The purpose of that boundary is not to prevent understanding, but to make understanding accountable to what actually occurred.

## 1. Purpose

### 1.1 Purpose of this standard

This publication defines the initial normative foundation for observation within Living Guide Technology. It establishes observation as a disciplined transformation of evidence into temporally and contextually bounded records that may later support interpretation, confidence, memory, reflection, and adaptation.

### 1.2 Constitutional basis

Living Guide Technology places the member's lived journey at the center and requires the Guide to remain loyal to evidence rather than previous conclusions. Observation is therefore prior to interpretation: the system must preserve enough distinction between what was available, what was observed, and what was inferred for later understanding to remain revisable and explainable.

### 1.3 Scope

This baseline governs the boundary among source evidence, observation, interpretation, and downstream derived understanding. It applies regardless of whether evidence originates from member statements, completed practices, application events, journals, connected systems, sensors, or other authorized sources.

It does not define confidence weighting, long-term memory retention, or reflective presentation. Those responsibilities belong to their respective LGT publications.

## 2. Foundational Definitions

### 2.1 Evidence

Evidence is source material available for accountable observation or interpretation. Evidence retains provenance and does not become more authoritative merely because it is stored, repeated, summarized, or retrieved frequently.

### 2.2 Observation

An observation is evidence that has been bounded by relevant source, time, context, and scope so that the system can state what was observed without silently adding a causal, predictive, diagnostic, or identity claim.

### 2.3 Interpretation

An interpretation is a revisable meaning proposed from one or more observations. Interpretation may identify possible relationships, patterns, or explanations, but SHALL remain distinguishable from the observations that support it.

### 2.4 Derived understanding

Derived understanding is a downstream representation formed from evidence, observations, interpretations, and applicable confidence processes. It SHALL NOT be represented as primary observation merely because it becomes useful or persistent.

## 3. Foundational Principle

### 3.1 Observation precedes interpretation

Where an implementation forms a material interpretation about a member, it SHALL preserve the observations or evidence basis necessary to distinguish the interpretation from what was directly observed.

### 3.2 Observation is bounded

An observation SHALL be bounded sufficiently to prevent context from being silently generalized beyond what the evidence supports. Relevant boundaries MAY include source, timestamp, temporal range, application context, member context, measurement conditions, or authorization state.

### 3.3 Observation does not claim causation

Co-occurrence, sequence, frequency, or correlation SHALL NOT by itself be recorded as causation. Causal interpretation requires separate justification and SHALL remain identifiable as interpretation unless independently established by an applicable evidence standard.

### 3.4 Observation does not define identity

A behavior, statement, preference, outcome, or repeated event MAY be observed. The observation SHALL NOT by itself become a fixed claim about the member's identity, character, destiny, diagnosis, or permanent nature.

## 4. Initial Architectural Requirements

### 4.1 Provenance preservation

Material observations SHALL retain recoverable provenance to the evidence from which they were formed. A reviewer SHOULD be able to determine the source class and relevant temporal context of an observation.

### 4.2 Source separation

Member statements, application events, imported records, sensor measurements, and system-generated interpretations SHALL remain distinguishable when their different origins materially affect meaning or authority.

### 4.3 Interpretation traceability

A material interpretation SHOULD be traceable to the observations that support it. The architecture SHALL NOT require a reviewer to accept an interpretation merely because the system generated it.

### 4.4 Uncertainty and missing context

Where evidence is incomplete, ambiguous, unavailable, or contextually limited, the observation SHOULD preserve that limitation. Missing context SHALL NOT be silently supplied by assumption.

### 4.5 Revision under new evidence

Observations MAY be corrected when their source, transcription, attribution, or contextual boundary is shown to be wrong. Interpretations SHALL remain revisable when later observations materially change the evidence base.

## 5. Relationship to LGT-MEM-001

LGT-MEM-001 - Memory Creates Continuity preserves observations, evidence provenance, and derived memory across time. LGT-OBS-001 defines the upstream discipline required before those observations enter longitudinal continuity. Memory preserves what the system has grounds to remember; Observation Before Interpretation governs how those grounds are bounded before memory relies upon them.

## 6. Baseline Conformance

### 6.1 Minimum baseline

For this draft baseline, an implementation materially aligned with LGT-OBS-001 SHALL distinguish observation from interpretation, preserve material provenance, retain relevant temporal or contextual boundaries, and avoid converting correlation, repetition, or inference into primary observation.

### 6.2 Non-conformance

A system is not aligned with this baseline when it invents observations, hides the evidence basis of material interpretations, silently converts inference into fact, treats missing context as known context, or converts observed behavior into fixed identity without accountable justification.

## 7. Observation Lifecycle

### 7.1 Evidence reception

Observation begins with evidence, not with a conclusion. An implementation SHALL preserve the evidence source and enough acquisition context to determine how the material entered the system. Evidence MAY originate from the member, an application event, a connected service, a device, a structured record, or another authorized source, but source class SHALL remain distinguishable.

### 7.2 Provenance attribution

Before evidence contributes to an observation, the implementation SHALL associate it with recoverable provenance. Provenance SHOULD include source identity or source class, relevant timestamp or temporal range, acquisition method where material, and any known transformation applied before observation formation.

### 7.3 Contextual bounding

An observation SHALL be bounded to the context actually supported by the evidence. The system SHALL NOT silently generalize an event observed in one setting, period, domain, or interaction into a universal statement about the member.

### 7.4 Temporal bounding

An observation SHALL preserve when the supporting evidence occurred or the period to which it reasonably applies. Where timing is uncertain, approximate, delayed, or reconstructed, that limitation SHOULD remain represented rather than being converted into false precision.

### 7.5 Source separation

Evidence from multiple sources MAY contribute to a related observation set, but the implementation SHALL preserve their distinct origins. Agreement among sources MAY strengthen later interpretation, but source convergence SHALL NOT erase provenance or convert several related records into a single invented observation.

### 7.6 Observation formation

An observation is formed when evidence has been attributed and bounded sufficiently to support a descriptive statement without requiring an explanatory conclusion. The observation SHALL remain traceable to its evidence and SHALL NOT contain causal, predictive, identity-based, or destiny-based claims unless those claims are themselves directly observed facts.

### 7.7 Transformation disclosure

Implementations MAY normalize, summarize, classify, or otherwise transform evidence to make observation practical. Material transformations SHALL remain accountable. The system SHOULD preserve enough information to distinguish source evidence from the transformed representation and to identify where meaning may have been compressed or generalized.

### 7.8 Uncertainty preservation

If evidence is incomplete, ambiguous, conflicting, or of uncertain provenance, the resulting observation SHALL preserve that uncertainty. Observation formation SHALL NOT be used to manufacture certainty that the evidence does not support.

### 7.9 Observation revision

An observation MAY be corrected, narrowed, superseded, or retired when better evidence becomes available. Revision SHALL preserve sufficient historical accountability to determine what changed and why without requiring the implementation to continue treating an outdated observation as current.

### 7.10 Handoff to interpretation and memory

Once an accountable observation has been formed, downstream systems MAY use it as input to interpretation under their applicable standards. LGT-OBS-001 governs the integrity of the observation boundary; it does not determine confidence, meaning, recommendation, or reflection. Where an observation is retained across time, LGT-MEM-001 governs continuity and provenance preservation.

## 8. Observation Classes and Source Boundaries

### 8.1 Classification preserves origin

An LGT implementation SHALL classify observation-relevant material sufficiently to preserve how the evidence originated and what kind of claim it can directly support. Classification SHALL describe source relationship and observation context; it SHALL NOT by itself assign truth, confidence, meaning, or importance.

### 8.2 Member-stated evidence

Material intentionally provided by the member about their own experience, preference, reflection, recollection, or account SHALL remain identifiable as member-stated evidence. The system MAY form observations that accurately represent what the member reported, but SHALL NOT silently convert the report into independently verified external fact.

### 8.3 Behavioral and application-event evidence

Actions recorded through an application or service MAY support observations about the recorded interaction. Such evidence SHALL remain bounded to what the event actually demonstrates. A click, completion, dismissal, duration, navigation event, or repeated use SHALL NOT by itself establish motive, belief, emotional state, preference, or identity.

### 8.4 Device and sensor evidence

Measurements from authorized devices or sensors MAY support observations within the measurement capability and known context of the source. The observation SHALL preserve relevant measurement provenance and SHALL NOT silently convert a measurement into a diagnosis, psychological conclusion, or causal explanation.

### 8.5 Imported and connected-source evidence

Records received from another application, service, archive, or interoperable LGT component SHALL remain identifiable as imported or externally sourced unless provenance demonstrates otherwise. Import SHALL NOT convert external material into first-party observation merely because the receiving implementation stores it locally.

### 8.6 System-generated evidence

An implementation MAY generate technical evidence about its own operation, such as recommendation presentation, model output, system state, error conditions, or interaction timing. System-generated evidence MAY support observations about system behavior but SHALL NOT be treated as independent evidence that the system's interpretation of the member was correct.

### 8.7 Human third-party evidence

Where an authorized implementation receives information supplied by another person about the member, that material SHALL remain attributable to the third-party source. The system SHALL distinguish that a statement was made from whether the content of the statement has been independently established.

### 8.8 Derived and transformed representations

Summaries, embeddings, classifications, normalized records, extracted features, or other transformed representations SHALL remain distinguishable from primary source evidence where the distinction materially affects interpretation. Transformation SHALL NOT create a new independent source merely because the representation is technically separate.

### 8.9 Corroboration without source collapse

Multiple source classes MAY describe related events or patterns. A later evidence or interpretation process MAY consider that convergence, but LGT-OBS-001 requires the underlying sources to remain distinguishable. Corroboration SHALL NOT erase disagreement, dependency, common origin, or transformation history.

### 8.10 Source reliability boundary

LGT-OBS-001 requires provenance, source classification, and preservation of known limitations. It does not assign universal reliability scores or confidence weights to source classes. A member statement, device measurement, application event, imported record, or third-party account may each be reliable or unreliable in context. Evaluation of evidentiary weight belongs to LGT-EVD-001.

## 9. Observation Conflict, Correction, and Supersession

### 9.1 Conflict SHALL remain observable

When two or more observations materially disagree, an implementation SHALL preserve the disagreement rather than silently merging the observations into a single apparently settled account. Conflict is information about the available evidence and SHALL remain distinguishable from resolution.

### 9.2 Contradiction does not determine evidentiary weight

The existence of contradiction SHALL NOT by itself determine which observation is correct, more reliable, or more important. LGT-OBS-001 preserves the conflicting observations, their provenance, temporal context, and known limitations. Evaluation of their evidentiary weight belongs to LGT-EVD-001.

### 9.3 Correction of observation records

An observation SHALL be corrected when the observation record inaccurately represents the evidence from which it was formed, including material transcription, attribution, timestamp, classification, or transformation errors. Correction SHALL restore fidelity to the supporting evidence and preserve sufficient accountability to determine that a correction occurred.

### 9.4 Member correction boundary

Where an observation represents member-stated evidence, an authorized member correction SHALL update what the system attributes to the member. The implementation SHALL NOT continue presenting an inaccurate member-attributed statement as current merely because it was recorded earlier. Correction of member attribution does not silently rewrite independently sourced evidence.

### 9.5 Supersession by later observation

A later observation MAY supersede an earlier observation when the later evidence describes a changed state or provides a more current account of the same bounded subject. Supersession SHALL NOT imply that the earlier observation was false when it was valid for its original time or context.

### 9.6 Narrowing and qualification

New evidence MAY require an observation to be narrowed or qualified rather than corrected or superseded. An implementation SHOULD preserve the most specific description supported by the evidence and SHALL NOT retain broader language when the known evidence no longer supports that breadth.

### 9.7 Withdrawal and invalidation

An observation MAY be withdrawn or invalidated when its supporting evidence is discovered to be unavailable, corrupted, misattributed, unauthorized, or otherwise incapable of supporting the observation. Downstream systems SHALL be able to distinguish an invalidated observation from an observation that remains valid but is no longer current.

### 9.8 Historical accountability

Correction, supersession, qualification, withdrawal, and invalidation SHALL preserve enough historical context to determine the prior observation state, the nature of the change, and the evidence or authorization condition that caused it. Historical accountability SHALL NOT require an outdated observation to continue influencing current interpretation.

### 9.9 No forced reconciliation

An implementation SHALL NOT manufacture a single reconciled observation when available evidence legitimately supports unresolved alternatives. Where reconciliation requires inference, judgment, confidence weighting, or explanation, that work belongs downstream of the observation boundary.

### 9.10 Handoff after change

When an observation materially changes status, downstream memory and evidence processes SHOULD receive enough information to reassess dependent understanding. LGT-MEM-001 governs continuity of the changed record across time; LGT-EVD-001 governs how the changed evidence affects confidence or competing interpretations.

## 10. Observation Dependency, Independence, Duplication, and Corroboration

### 10.1 Independence SHALL be evidence-based

Two observations SHALL NOT be treated as independent merely because they are stored separately, produced by different components, expressed in different formats, or observed at different processing stages. Independence requires that the supporting evidence does not materially depend on the same originating event, record, transformation, or upstream source in a way relevant to the observation.

### 10.2 Common-source ancestry

Where multiple observations descend from the same primary evidence, their common-source ancestry SHALL remain recoverable when that dependency could affect downstream interpretation. Copies, exports, synchronized records, cached representations, and replicated events SHALL NOT silently become independent corroborating sources.

### 10.3 Derived-observation dependency

An observation formed from another observation, summary, classification, extraction, or transformed representation SHALL retain sufficient dependency information to identify the upstream basis. Derivation MAY create a useful new representation, but SHALL NOT create new independent evidence by transformation alone.

### 10.4 Duplicate evidence

Exact or materially equivalent duplicate evidence MAY be retained for operational reasons, but duplication SHALL NOT be represented as additional independent observation support. Implementations SHOULD detect known duplication where practical and SHALL preserve enough provenance to prevent known copies from masquerading as corroboration.

### 10.5 Partial dependency

Observations MAY share some evidence while also containing independently sourced support. An implementation SHOULD preserve enough dependency structure to distinguish the shared basis from genuinely independent material. Partial independence SHALL NOT be simplified into either total independence or total duplication when that distinction materially affects later evaluation.

### 10.6 Temporal repetition is not automatic independence

Repeated observations across time MAY constitute distinct evidence when they arise from genuinely separate events or measurements. Repetition alone, however, SHALL NOT establish independence. Automated re-reporting, periodic synchronization, recurring summaries, or repeated retrieval of the same underlying record remain dependent on that underlying source.

### 10.7 Cross-system duplication

The same evidence MAY enter an LGT ecosystem through multiple connected systems. Where common origin is known or reasonably recoverable, implementations SHALL preserve that relationship. Technical diversity of transport or storage SHALL NOT be mistaken for evidentiary diversity.

### 10.8 Corroboration requires distinguishable support

An observation MAY be described as corroborated only when multiple supporting evidence relationships remain distinguishable and the claim of corroboration does not conceal known dependency. LGT-OBS-001 requires structural honesty about the support; it does not determine how much confidence corroboration should add.

### 10.9 Unknown dependency SHALL remain unknown

When an implementation cannot determine whether apparently separate evidence shares a common source, it SHALL NOT assert independence as fact. The dependency state SHOULD remain unknown or qualified until sufficient provenance is available.

### 10.10 Dependency changes SHALL propagate

If evidence previously treated as independent is later discovered to be duplicated, derived, or commonly sourced, the observation record SHOULD be updated so downstream systems can reassess any interpretation that relied on false independence. Historical accountability SHOULD preserve why the dependency classification changed.

### 10.11 Boundary with evidentiary weighting

LGT-OBS-001 governs whether observation support is independent, dependent, duplicated, transformed, partially shared, or unknown to the extent that provenance permits. LGT-EVD-001 governs what evidentiary weight those relationships contribute to confidence. Structural independence is therefore an input to evidence evaluation, not a confidence score by itself.

## 11. Observation Scope, Granularity, Aggregation, and Decomposition

### 11.1 Observation scope SHALL match evidence scope

An observation SHALL describe no more than the evidence directly supports. Evidence bounded to a particular event, interaction, period, source, domain, or condition SHALL NOT be silently expanded into a broader statement about the member.

### 11.2 Granularity SHALL remain proportional

Observation granularity SHOULD be fine enough to preserve material distinctions in the supporting evidence and broad enough to remain useful for continuity. Implementations SHALL NOT combine materially different evidence merely to simplify storage or presentation when doing so changes what can responsibly be observed.

### 11.3 Aggregation SHALL preserve constituent observations

Multiple observations MAY be grouped into an observation set when they concern a related subject, period, or context. Aggregation SHALL preserve the identity, provenance, temporal bounds, and dependency relationships of the constituent observations where those distinctions materially affect later interpretation.

### 11.4 Aggregation does not create a broader fact

The existence of several narrow observations SHALL NOT by itself establish a broader observation that exceeds their combined descriptive support. A collection of completed practices, repeated visits, journal entries, or similar events may establish that those events occurred; it SHALL NOT silently establish motive, identity, preference, transformation, or enduring pattern.

### 11.5 Summary representations remain summaries

An implementation MAY create a summary of an observation set for usability or interoperability. The summary SHALL remain identifiable as a transformed representation and SHOULD preserve access to the observations from which it was formed. Compression SHALL NOT erase material disagreement, uncertainty, temporal variation, or source dependency.

### 11.6 Decomposition of compound observations

Where a proposed observation contains multiple materially separable claims supported by different evidence, contexts, or time periods, the implementation SHOULD decompose it into bounded observations. A compound statement SHALL NOT conceal that one component is directly observed while another requires inference.

### 11.7 Cross-domain aggregation boundary

Observations from different domains MAY be related downstream, but OBS SHALL NOT merge them into a cross-domain conclusion merely because they concern the same member. Behavioral, reflective, physiological, social, spiritual, or application-use observations retain their domain context unless evidence directly supports a shared descriptive observation.

### 11.8 Temporal aggregation boundary

Repeated observations MAY be represented as a temporally bounded series or set. The system SHALL preserve enough temporal structure to distinguish recurrence, persistence, interruption, and change. Historical repetition SHALL NOT silently become a claim of present continuity.

### 11.9 Absence within an aggregate

Missing observations within a period or set SHALL remain distinguishable from observations of absence. A gap in collected evidence SHALL NOT be filled with an invented neutral state merely to make an aggregate appear complete.

### 11.10 Reversible aggregation

Where aggregation materially affects downstream understanding, the implementation SHOULD preserve sufficient structure for a reviewer or downstream component to recover the contributing observations and their relevant boundaries. Aggregation SHOULD add organization without destroying traceability.

### 11.11 Boundary with interpretation

OBS may organize observations into bounded sets, sequences, or summaries, but SHALL NOT convert organization into explanatory meaning. Claims that a set demonstrates a pattern, cause, preference, trajectory, archetype, or likely future state require downstream interpretation and evidence evaluation.

## 12. Observation Authorization, Consent, and Purpose Boundaries

### 12.1 Observation requires an authorized basis

Evidence SHALL participate in observation only when the implementation has an applicable authorized basis to receive and use it for that observation purpose. Technical access to evidence SHALL NOT by itself establish authorization to observe, retain, combine, or reuse it.

### 12.2 Authorization state SHALL remain attributable

Where authorization materially affects whether evidence may be observed or reused, the implementation SHALL preserve enough authorization context to determine the applicable source, purpose, scope, and known limitations. Authorization metadata MAY be represented separately from the observation record provided the relationship remains recoverable.

### 12.3 Consent SHALL be purpose-bounded

Where member consent is the applicable authorization basis, consent SHALL be interpreted according to the purpose and scope for which it was given. Consent to collect or use evidence for one function SHALL NOT silently become unrestricted permission to use the same evidence for unrelated observation purposes.

### 12.4 Collection SHALL remain proportional to observation purpose

An implementation SHOULD collect or expose to the observation process only the evidence reasonably necessary for the declared continuity purpose. The ability to collect additional information SHALL NOT make maximal collection an architectural objective.

### 12.5 Purpose SHALL travel with continuity-relevant observation

When an observation moves between components or implementations, material purpose limitations SHOULD remain available to the receiving context. Transfer SHALL NOT erase a known restriction merely because the receiving component is technically capable of additional use.

### 12.6 Revocation SHALL affect future observation use

Where authorization or consent is revoked, withdrawn, or expires, the implementation SHALL stop future observation use that depends on that authorization unless another applicable basis permits the use. Revocation SHALL NOT be treated as evidence that previously authorized observations were false.

### 12.7 Changed purpose requires renewed authority

If an implementation seeks to use evidence or observations for a materially different purpose from the one under which they were obtained, it SHALL establish an applicable authorization basis for the changed purpose before that use occurs. Historical possession SHALL NOT substitute for current authority.

### 12.8 Sensitive expansion SHALL NOT be inferred from general authorization

General authorization to observe one domain SHALL NOT be interpreted as permission to observe materially different domains merely because the system can technically connect them. Cross-domain observation requires authorization appropriate to the additional evidence and purpose.

### 12.9 Authorization gaps SHALL remain visible

If the system cannot determine whether evidence is authorized for a proposed observation use, it SHALL NOT silently assume unrestricted permission. The authorization state SHOULD remain unknown, restricted, or otherwise qualified until resolved.

### 12.10 Removal and authorization boundaries

Where evidence must be removed or made unavailable because authorization no longer permits its retention or use, dependent observations SHALL be reassessed according to their remaining support. The system SHALL NOT preserve a derived observation as active merely to circumvent a restriction on the evidence required to justify it.

### 12.11 Observation is not a general privacy standard

LGT-OBS-001 defines authorization, consent, collection, and purpose requirements only to the extent necessary to preserve accountable observation boundaries. It does not replace applicable privacy law, security requirements, data-governance policy, retention obligations, or broader LGT governance standards. Implementations SHALL satisfy those independent obligations in addition to this publication.

## 13. Observation Auditability, Explainability, and Reviewability

### 13.1 Observation SHALL be reconstructable

An implementation SHALL preserve enough information for an authorized reviewer or downstream component to determine what was observed and the material basis from which the observation was formed. Reconstruction SHALL NOT require treating an interpretation, summary, or current system state as a substitute for the observation's actual provenance.

### 13.2 Evidence basis SHALL be traceable

An observation SHALL remain traceable to the evidence relationships that materially support it. Traceability MAY use identifiers, provenance records, references, dependency graphs, or equivalent mechanisms, but SHALL allow the implementation to distinguish supporting evidence from contextual or unrelated material.

### 13.3 Material transformations SHALL be reviewable

Where normalization, extraction, summarization, classification, aggregation, or another transformation materially affects the observation, the transformation SHALL remain reviewable at a level sufficient to understand how the representation differs from its source. Reviewability does not require disclosure of proprietary implementation details that are unnecessary to evaluate the observation boundary.

### 13.4 Bounds SHALL be explainable

An implementation SHOULD be able to identify the material temporal, contextual, source, authorization, and scope boundaries applied to an observation. Where a bound is unknown or approximate, the explanation SHALL preserve that limitation rather than presenting false precision.

### 13.5 Observation status SHALL be visible

A reviewer SHOULD be able to determine whether an observation is current, corrected, superseded, qualified, withdrawn, invalidated, or otherwise limited when that status materially affects downstream use. Historical existence SHALL NOT be confused with current authority.

### 13.6 Change history SHALL be accountable

Material changes to an observation SHOULD preserve enough audit context to identify the prior state, the resulting state, and the reason or evidence condition that caused the change. Auditability SHALL support revision rather than make prior observations artificially immutable.

### 13.7 Dependency SHALL be reviewable

Where independence, duplication, derivation, common-source ancestry, or partial dependency materially affects an observation, an authorized reviewer SHOULD be able to inspect or recover that relationship. A system SHALL NOT claim independent corroboration while withholding a known dependency that materially changes the claim.

### 13.8 Authorization limitations SHALL remain reviewable

Where authorization or purpose limitation affects whether evidence may support an observation, the applicable restriction SHOULD remain recoverable to an authorized reviewer. Auditability SHALL NOT itself expand access to restricted evidence or override the authorization boundary being reviewed.

### 13.9 Review under restricted or removed evidence

When underlying evidence cannot be disclosed or has been removed, the implementation MAY preserve limited audit metadata necessary to represent that the observation's basis is restricted, unavailable, or removed, subject to applicable authorization and retention obligations. Such metadata SHALL NOT be used to reconstruct prohibited content or to preserve a derived claim that no longer has sufficient authorized support.

### 13.10 Explainability SHALL describe observation formation, not invent meaning

OBS explainability concerns what evidence participated, how it was bounded, what transformations occurred, and what status or dependency conditions apply. It SHALL NOT require the observation layer to explain why the member behaved a certain way, what an experience means, what will happen next, or what identity the observation implies.

### 13.11 Reviewer access SHALL be proportionate

Review mechanisms SHOULD expose enough information to evaluate conformance without unnecessarily disclosing unrelated member information, restricted evidence, security-sensitive implementation details, or other data outside the review purpose.

### 13.12 Audit records are not independent evidence

Logs, provenance records, review records, and audit metadata MAY demonstrate how an observation was formed or changed. They SHALL NOT be treated as independent corroborating evidence for the underlying member observation merely because they record the system's processing of it.

### 13.13 Boundary with reflective explanation

LGT-OBS-001 requires observation formation to be accountable and reviewable. It does not prescribe how a Living Guide communicates interpretations, confidence, reflections, or guidance to the member. Those presentation and relationship responsibilities remain governed by downstream LGT publications, including LGT-EVD-001, LGT-MIR-001, and LGT-CMP-001.

## 14. Conformance and Review Tests

### 14.1 Evidence-to-observation trace test

A reviewer SHALL be able to select a material observation and recover the evidence relationships that support it.

**Pass condition:** supporting evidence, provenance, material transformations, and applicable bounds are recoverable.

**Non-conformance:** the observation exists as an unsupported system assertion or its material basis cannot be distinguished from later interpretation.

### 14.2 Observation-versus-interpretation test

A reviewer SHALL be able to determine whether a statement records what was observed or introduces explanatory, causal, predictive, identity-based, or other interpretive meaning.

**Pass condition:** interpretive content is distinguishable from accountable observation.

**Non-conformance:** inference is silently stored or presented as primary observation.

### 14.3 Source-class preservation test

A reviewer SHOULD be able to distinguish member-stated, behavioral/application-event, device/sensor, imported, system-generated, human third-party, and transformed evidence where those distinctions materially affect interpretation.

**Pass condition:** source class and provenance remain recoverable.

**Non-conformance:** storage or transformation silently converts evidence into a different source class.

### 14.4 Dependency and duplication test

Where multiple observations appear to corroborate one another, a reviewer SHOULD be able to identify known common-source ancestry, duplication, derivation, or partial dependency.

**Pass condition:** known dependency remains visible and is not represented as independent corroboration.

**Non-conformance:** copies, summaries, synchronized records, or transformations manufacture apparent evidentiary independence.

### 14.5 Scope and aggregation test

A reviewer SHALL be able to determine whether an observation remains within the scope directly supported by its evidence.

**Pass condition:** aggregation preserves constituent boundaries and does not silently create broader facts.

**Non-conformance:** bounded events are converted into unsupported claims about motive, preference, identity, transformation, trajectory, or enduring pattern.

### 14.6 Conflict-preservation test

Where material observations disagree, a reviewer SHOULD be able to identify the unresolved conflict and each observation's relevant provenance and context.

**Pass condition:** disagreement remains represented until a responsible downstream process evaluates it.

**Non-conformance:** the observation layer silently chooses, merges, or invents a reconciled account requiring inference.

### 14.7 Correction and supersession test

A reviewer SHALL be able to distinguish correction of an inaccurate record from supersession caused by later or changed evidence.

**Pass condition:** the current state is identifiable and material historical change remains accountable.

**Non-conformance:** revision silently erases history or an outdated observation retains authority merely because it existed first.

### 14.8 Authorization and purpose test

Where authorization materially limits observation use, a reviewer SHOULD be able to determine the applicable purpose or restriction without the review mechanism itself overriding that restriction.

**Pass condition:** observation use remains within applicable authorization and purpose boundaries.

**Non-conformance:** technical possession or access is treated as unrestricted authority.

### 14.9 Auditability test

A reviewer SHALL be able to reconstruct material observation formation without relying on the system's current interpretation as proof of what occurred.

**Pass condition:** observation state, evidence basis, material transformations, bounds, and relevant changes remain reviewable.

**Non-conformance:** the system can state an observation but cannot account for how it was formed.

### 14.10 Gap-honesty test

A reviewer SHOULD be able to identify material gaps in provenance, timing, dependency, authorization, or evidence availability.

**Pass condition:** unknown or unavailable information remains represented as a limitation.

**Non-conformance:** missing information is silently converted into certainty, neutrality, absence, or completeness.

### 14.11 Conformance record

A conformance assessment SHOULD record the publication version evaluated, implementation version, test scope, evidence examined, limitations, and result. Passing assessment against v0.9.0 SHALL NOT be treated as permanent certification of later publication or implementation versions.

## 15. Release-Readiness Safeguards and Normative Coherence

### 15.1 Observation SHALL NOT become identity

A Living Guide SHALL NOT treat accumulated observations as a complete or permanent representation of the member. Observations describe bounded evidence about experiences, behavior, statements, measurements, interactions, or conditions; they do not define the person's essence, destiny, diagnosis, or fixed identity.

### 15.2 Repetition SHALL NOT convert observation into interpretation

Repeated observation MAY provide additional evidence that an event or behavior recurred. Repetition SHALL NOT by itself convert descriptive observation into motive, meaning, preference, pattern, cause, or prediction.

### 15.3 Observation SHALL remain temporally bounded

Where evidence supports an observation primarily for a particular period, the implementation SHOULD preserve that temporal boundary. Historical consistency SHALL NOT be silently projected into the present without current evidence.

### 15.4 Observation SHALL preserve the possibility of change

The architecture SHALL permit later evidence to correct, narrow, qualify, supersede, or invalidate earlier observations. A system that technically preserves new evidence but structurally privileges old observations so they cannot meaningfully change current understanding is non-conforming to the principles defined here.

### 15.5 Absence of observation is not observation of absence

Failure to collect, receive, retain, access, or form an observation SHALL NOT be interpreted as evidence that an event, state, preference, behavior, or experience did not occur. Missing observation is a limitation of available evidence, not a factual claim about the person.

### 15.6 Observation SHALL NOT imply confidence

An accountable observation may be well or poorly supported depending on its evidence and context, but LGT-OBS-001 does not assign confidence merely because an observation exists. Confidence semantics and evidentiary weighting belong to LGT-EVD-001.

### 15.7 Observation SHALL NOT imply authority

The existence of a system-recorded observation SHALL NOT grant the system superior authority over the member's lived account. Where member-stated evidence and system-derived observation differ, the disagreement SHALL remain accountable rather than being resolved by assuming the system is inherently authoritative.

### 15.8 Terminology SHALL remain consistent

Normative terms in this publication SHALL retain their established meanings across sections. Observation, evidence, interpretation, provenance, source class, dependency, aggregation, correction, supersession, authorization, and review SHALL NOT be silently redefined for implementation convenience.

### 15.9 Normative language

The keywords SHALL, SHALL NOT, SHOULD, SHOULD NOT, MAY, and MAY NOT express requirement strength in this publication. SHALL and SHALL NOT identify mandatory conformance requirements. SHOULD and SHOULD NOT identify strong recommendations that may be departed from only with documented rationale. MAY and MAY NOT identify permitted implementation choices.

### 15.10 Cross-publication responsibility boundaries

Where LGT-OBS-001 references another LGT publication, the reference establishes an architectural boundary rather than importing undefined behavior into this standard. LGT-MEM-001 governs continuity and provenance across time; LGT-EVD-001 governs evidence weighting and confidence; LGT-MIR-001 and LGT-CMP-001 govern reflective presentation and companion relationship behavior. LGT-OBS-001 remains responsible for the accountable formation and preservation of observation boundaries.

### 15.11 Release-readiness determination

Following review against the requirements and constitutional commitments represented in this publication, no additional major observation domain is introduced by this release. Remaining work before v1.0.0 is final consistency verification, render verification, release metadata, and publication preparation. New normative scope SHOULD be added before v1.0.0 only when a demonstrable architectural gap is identified.

## 16. Closing Baseline Statement

Observation Before Interpretation establishes a simple but foundational discipline: a Living Guide may interpret, but it must remain able to show what came before the interpretation. Understanding becomes trustworthy not because interpretation is forbidden, but because interpretation remains accountable to observation and observation remains accountable to evidence.
