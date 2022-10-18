# DSA-Project
Missing Ocko-Bong 221134589
Gad Mukoj Katangal 222003383
John Krohne 222051205
Tanaka Lynn Tadyanemhandu 222007141
Antonio Tooleni Junior Daniel 222108517
Gatsi Tashinga 222062614
Mutonj Ali Bota 222125144
Sara Nakale 222051132
Shalom Chiwaula 222001046
Nomo Lyric Benjamin 222005459
Team Leader: Nomo Lyric Benjamin, benjaminnomolyric@gmail.com, 0817050289.

 
Section A
START
   function createPlaylist()
  tracks = 100
  linkedList = createNewLinkedLIst()
  for (i=0 to tracks -1) {do
  add Track(linkedlist, i)}
  end for

  return linkedList
  end function
  function playTrack(linkedList, trackNumber)
  currentTrack = currentTrack.next
  end for

  playAudio(currentTrack.data)
  end function
  function addTrack(linkedList, trackNumber)
  newTrack = createNewTrack(trackNumber)
  if(linkedList.head = null) { then
  linkedList.head = newTrack}
  else {currentTrack = linkedList.head}
  while (currentTrack.next != null) { do 
  currentTrack = current_track.next}
  end while
  currentTrack.next = newTrack
  endif
   end function

   function removeTrack(linkedList, trackNumber
   currentTrack = linkedList.head
   previousTrack = null
  for (i = 0 to trackNumber – 1) { do
 previousTrack = currentTrack
 currentTrack = currentTrack.next
 }
 End for

 If (previousTrack = null) {then
linkedList.head = currentTrack.next}
else {previousTrack.next = currentTrack.next}
 end if
 end function

function browsePlaylist(linkedList, trackNumber)
currentTrack = linkedList.head
while (currentTrack != null) {do
if (currentTrack.data = trackNumber) {then
return true}
end if
currentTrack = currentTrack.net
}
end while
return false
end function
End 
