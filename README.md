## Programming Worktest
<p>
This is a programming test I did for an intership position. The task was to use Advanced Locomotion System in Unreal Engine 4 and to modify the demo scene to create a red light, green light game for the AI.
</p>
<p>
  
#### Files Added under ‘Content/AdvancedLocomotion/Blueprints/CharacterLogic/AI/’    
  
* AIC_Curator  
  + AI Controller for the curator  
* BT_Curator  
  + Behaviour tree for the curator  
* BTTask_TurnAround   
  + Behaviour Tree Task for the curator  
* BTService_KillMovingParticipants  
  + Behaviour Tree Service for the curator  
* BTTask_GetTargetPosition  
  + Behaviour Tree Task for the participants  
</p>
<p>
  
#### Files modified   
  
* ALS_DemoLevel  
  + Expanded navmesh volume and added walls for the play area   
  + Added countdown code to Level Blueprint  
* ALS_BT_AICharacter  
  + Added some time variance to the movement  
* ALS_BTTask_GetRandomLocation  
  + Renamed to BTTask_GetTargetPosition and repurposed to move straight.
</p>
