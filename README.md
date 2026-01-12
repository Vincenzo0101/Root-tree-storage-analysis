# Root-tree-storage-analysis
A ROOT utility macro that reports detailed storage usage of TTrees and their branches

---
## Example Usage

root [] printTreeSummary(tree);
The TTree "T" takes 3764343 bytes on disk
  It's branch "event" takes 3760313 bytes on disk

root [] printBranchSummary(tree->GetBranch("event"));
The branch "event" takes 3760313 bytes on disk
  It's sub-branch "TObject" takes 581 bytes on disk
  It's sub-branch "fType[20]" takes 640 bytes on disk
  It's sub-branch "fEventName" takes 855 bytes on disk
  It's sub-branch "fNtrack" takes 506 bytes on disk
  It's sub-branch "fNseg" takes 554 bytes on diskTBranch *br = tree->GetBranch("InDetTrackParticles");
  It's sub-branch "fNvertex" takes 507 bytes on disk
  It's sub-branch "fFlag" takes 420 bytes on disk
  It's sub-branch "fTemperature" takes 738 bytes on disk
  It's sub-branch "fMeasures[10]" takes 1856 bytes on disk
  It's sub-branch "fMatrix[4][4]" takes 4563 bytes on disk
  It's sub-branch "fClosestDistance" takes 2881 bytes on disk
  It's sub-branch "fEvtHdr" takes 847 bytes on disk
  It's sub-branch "fTracks" takes 3673982 bytes on disk
  It's sub-branch "fHighPt" takes 59640 bytes on disk
  It's sub-branch "fMuons" takes 1656 bytes on disk
  It's sub-branch "fLastTrack" takes 785 bytes on disk
  It's sub-branch "fWebHistogram" takes 596 bytes on disk
  It's sub-branch "fH" takes 10076 bytes on disk
  It's sub-branch "fTriggerBits" takes 1699 bytes on disk
  It's sub-branch "fIsValid" takes 366 bytes on disk
